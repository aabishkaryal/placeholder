# Placeholder:
Download placeholder images from <https://via.placeholder.com>.  

## Installation:


## Usage:
```
placeholder.py [-h] [-bc BGCOLOR] [-fc FGCOLOR] [-t TEXT] [-e EXT] [-p PATH] [-c COUNT] size

Get placeholder image from via.placeholder.com

positional arguments:
  size         dimensions of the image.

optional arguments:
  -h, --help   show this help message and exit
  -bc BGCOLOR  background color of image (default: cdcdcc)
  -fc FGCOLOR  foreground color of image (default: 9g9797)
  -t TEXT      text to be displayed on image (default: <width>x<height>-<count>)
  -e EXT       extension of image (default: png)
  -p PATH      path to save image (default: os.getcwd())
  -c COUNT     number of images to be generated (default: 1)
```