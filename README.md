# Sound sprites
This script does 2 things:
1. Merges all OGG and MP3 files from `./sounds` directory into two `./sprite.ogg` and `./sprite.mp3`
2. Generates a JSON file with information about the millisecond from which the sound is in the output file and how many milliseconds it lasts. This file you can usage in howler.js - JavaScript audio library

# Usage
1. Run `python -m pip install pydub`
2. Create directory `./sounds` then put your `ogg` and `mp3` files to this
3. Run `make.cmd`
