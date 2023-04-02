## A free and open source 80's interpretation of a famous falling brick gameplay.

* Made with Python and Pygame on and for the Raspberry Pi 400.

I like the idea to have a library of open source games with a eigties feel for the RPI400 computer like if it was a computer coming from this long forgotten era where amiga, atari or amstrad was magical names.

I made the game from memory, so I am not sure I differ enough from the original gameplay, still it is not commercial product, it is remade for it's historical & educational value.

### Features :

* Ingame help & instructions.
* Two point types, the score will grow depending on the level and the speed points will grow until 100 to switch to next level. 
* Maybe around 16 colors, but mostly only 2, also with modern "Borrowed" sound and music.
* Play with the keyboard or with the gamepad.
* The scores are saved in a separate file (save.csv). Display the 8 best scores on the HIGHSCORES Board. The file is generated if file not found or corrupted.
* The game is over when 100 speed point at last level (9) are reached. Max time before game over is 1 hour, 1 minute & 1 seconde, but probably impossible to reach.
* Use "F" key to switch into fullscreen mode. (I haven't kept fullscreen by default, there is some trouble right now around fullscreen mode on Ubuntu based linux distribution, maybe you will need to compile pygame on those platform to get it working.)
* Use "S" key to switch music on/off

### Releases :

* On github as code and on itchio for the Raspberry Pi 400, see releases.

### Dependencies :

It should work fine with a python 3.7+ version, but be careful as it requires the recent pygame 2 release (will crash with 1.9 versions, mostly because I use the SCALED new feature).
Probably necessary a lot of SDL libraries to install if the game don't start.

Install Dependcies

pip3 install pygame==2

sudo apt-get install libsdl2-2.0-0   

sudo apt-get install libsdl2-2.0-0 

sudo apt-get install libsdl2-image-2.0-0

sudo apt-get install libsdl2-mixer-2.0-0  

sudo apt-get install libsdl2-ttf-2.0-0 


### Start the game :


In the root directory :

```
python game.py
```
* **python3** on linux, if python is the version 2

