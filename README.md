# gb_map_converter

Takes a PNG of a map and generates the [GBDK 2020](https://github.com/gbdk-2020/gbdk-2020) files using [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv).

## Arguments

Argument | Description
------------ | -------------
-i, --input | Required. Input image to be converted.
-a, --auto-output | Output in the same folder as the input image.
-o, --output | (Overrides auto-output) Output folder to place converted files.
-n, --name | Name to use for converted files and variables.
-t, --tiles | (Default: false) Create a tiles image file.
-p, --palette | (Default: false) Create a palette image file.
-b, --bank | (Default: 255) Specify bank number. Use 0 to disable.
-l, --lower | (Default: false) Use lowercase variables instead of uppercase.
-v, --verbose | (Default: false) Show more information.
--help | Display this help screen.
--version | Display version information.


## Download
[Download the latest release.](https://github.com/borg100/gb_map_converter/releases/latest)
