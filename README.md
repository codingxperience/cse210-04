# cse210-04
CSE210, Week 8 team group assignment, Greed


# Greed
Dozens of rocks and gems will be falling from above. Try to catch as many gems as possible to get points, but beware of the rocks. You will lose twice as many points if you get hit by a rock. You can move left, right and up or down in limited range. This is the Greed game.


## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.

```
python3 -m pip install raylib

```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.

```
python3 greed

```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.


## Project Structure
---
The project files and folders are organized as follows:
```
root                   	         (project root folder)
  +--__main__.py		             (program entry point)
  +--README.md			             (general info)
  +--game/
    +--casting/
      +--actor.py                (game class with methods)
      +--cast.py                 (game class with methods)
      +--gem.py                  (game class with methods)
      +--rock.py                 (game class with methods)
    +--directing/
      +--director.py             (game class with methods)
    +--services/
      +--keyboard-services.py    (game class with methods)
      +--video-services.py       (game class with methods)
    +--shared/
      +--color.py                (game class with methods)
      +--point.py                (game class with methods)


```

## Required Technologies
---
* Python 3.10.1
* raylib

## Authors
---
* Fred Okorio (mailto:oko22002@byui.edu)
* Mmusi Hubona (mailto:hub22001@byui.edu)
* Vaughn Pinnock (mailto:vpinnock@byui.edu)