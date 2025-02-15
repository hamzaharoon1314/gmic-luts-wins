# GMIC LUTs - For Windows

# This Project is a Fork of [Popul-AR/gmic-luts](https://github.com/Popul-AR/gmic-luts/)

This project translates the built-in [GMIC LUTs](https://gmic.eu/color_presets/) to various formats, using a bash script. Preview images are generated for human eyes.


![collection](./docs/collection.jpg)

## Formats

### Cube16: Snapchat Lens Studio format

<img width="200" alt="neutral-cube16" src="./neutral-luts/neutral-cube16.png">

### Cube32: Spark AR native format

<img width="200" alt="neutral-cube32" src="./neutral-luts/neutral-cube32.png">

### Hald8: GMIC and ImageMagick format

<img width="200" alt="neutral-hald8" src="./neutral-luts/neutral-hald8.jpg">

### Hypercube: Spark AR FastColorLUT format (and common webgl)

<img width="200" alt="neutral-hypercube" src="./neutral-luts/neutral-hypercube.png">


## Usage

[Requires GMIC](https://gmic.eu/index.html)

Run `bash generate-luts.ps1` on the Powershell.

To change the preview image, replace test.jpg with your own image. 

Any image-based format can be supported just by adding a new neutral lut and editing the script. 
