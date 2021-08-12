# T-Rex Rush Like Gym

![](https://github.com/shivamshekhar/Chrome-T-Rex-Rush/raw/master/screenshot.png)

![](https://github.com/shivamshekhar/Chrome-T-Rex-Rush/raw/master/screenshot.gif)

### Description:
A recreated version of the famous Chrome T-Rex in Python for reinforcement learning.

This repository was changed to allow the game be controlled by other programs, like [Chrome_T-Rex_Rush_IA](https://github.com/MaxwellFB/Chrome_T-Rex_Rush_IA).

### Technology:
Built using pygame library

### Version and Release:
Reinforcement learning release, version 1.0

### Instructions and Prerequisites:
* Python v3.8.10
* Pygame v2.0.1

##### How to start: 
    from Chrome_T_Rex_Rush_Like_Gym import main as dinoGame
	dino = dinoGame.GameDino()
	dinoGame.introscreen()
	dino.reset_game()

##### Controls:
0 = do nothing

1 = jump

2 = crouch

3 = close game

    isGameQuit, isGameOver = dino.play(action)

##### Restart game after game over:
    dino.reset_game()

##### Close game:
    dino.play(3)

OR

    dino.quit()

### Developed by: 
Shivam Shekhar  
Email: shivamshekhar299@gmail.com

#### Changed by:
* **Maxwell F. Barbosa** - [MaxwellFB](https://github.com/MaxwellFB)

#### Credits:
* Sprites : https://chromedino.com/assets/offline-sprite-2x-black.png
* Logo : https://textcraft.net/
* Speech Bubble : http://pixelspeechbubble.com/
* Sounds : https://github.com/vicboma1/T-Rex-Game/tree/master/Unity/Sounds

#### References:
* http://www.pygame.org/docs
* https://github.com/wayou/t-rex-runner
