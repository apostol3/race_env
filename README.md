# Race environment for nlab

Require: [pynlab](https://github.com/Apostol3/pynlab),
[Box2D](https://github.com/pybox2d/pybox2d),
[pygame](http://www.pygame.org/download.shtml)

````
usage: main.py [-h] [-p name] [-c n] [--no-gui] [--challenge] [file]

positional arguments:
  file                  map file (default: default.json)

optional arguments:
  -h, --help            show help message and exit
  -p name, --pipe name  pipe name (default: nlab)
  -c n, --count n       number of players (default: 25)
  --no-gui              do not show gui
  --challenge           challenge mode with collisions
````

Also you can launch in "manual" mode. To do this run `race_env.py` file.
Controls - Arrow keys. Press Enter to restart environment.

````
usage: race_env.py [-h] [--challenge] [file]

positional arguments:
  file         map file (default: default.json)

optional arguments:
  -h, --help   show help message and exit
  --challenge  challenge mode with collisions
````

###Screenshot of custom map:
![screenshot](./screenshot.png)