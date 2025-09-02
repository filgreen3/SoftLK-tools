# SoftLK-tools

This repo hosts the source code for different (currently two) programs made by Lukas Holzbeierlein (Captain4LK).

## Programs

More information, compilation instructions and download links can be found in the tools respective READMEs.

|Program|Info|Version|
|---|---|---|
|[SLK_img2pixel](SLK_img2pixel/README.md)|A tool for transforming images into pixel art|1.5|
|[SLK_make](SLK_make/README.md)|A build system based on the one used by golgotha|on hold|

# Gallery

![SLK_img2pixel_preview](screenshots/SLK_img2pixel.png)

# Contact

Here is a link to the SLK_img2pixel Discord. Feel free to pop in and make suggestions or ask questions: https://discord.gg/Nch8hjdZ2V

# Download 

* SLK_img2pixel: [itch.io](https://captain4lk.itch.io/slk-img2pixel)

# Building for macOS

Instructions for building `SLK_img2pixel` on macOS.

1.  **Install Prerequisites:**
    *   Install Xcode Command Line Tools: `xcode-select --install`
    *   Install Homebrew from [brew.sh](https://brew.sh/).
    *   Install libraries: `brew install sdl2 pkg-config`

2.  **Compile:**
    *   Navigate to the tool's directory: `cd SLK_img2pixel`
    *   Generate the Makefile: `./macos.sh > Makefile`
    *   Run make: `make`

3. **Done:**
    *   Run `SoftLK-tools/bin/SLK_img2pix`

# License

All code in this repository (except the 'external' directory containing source code not by me) is released into the public domain (CC0), see COPYING for more info.

# Planned tools / ideas

* tile map editor
* pixel art editor

# Third party libraries

* [tinyfiledialogs](https://sourceforge.net/projects/tinyfiledialogs/), zlib, for all builds except windows
* [stb_image](https://github.com/nothings/stb), mit/unlicense
* [fopen_utf8](https://github.com/Photosounder/fopen_utf8/), only for windows builds, public domain
* [Native File Dialog Extended](https://github.com/btzy/nativefiledialog-extended), only for windows builds, zlib
