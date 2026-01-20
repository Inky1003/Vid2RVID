# Vid2RVID - Linux port

Linux port of the Rocket Video (`.rvid`) converter, from https://github.com/RocketRobz/Vid2RVID

Requires [ImageMagick](https://imagemagick.org/) installed, and `magick` command available in PATH.

Converted video files can be run with [Rocket Video Player](https://github.com/RocketRobz/RocketVideoPlayer)

# Usage

Open a terminal, then run:

```cmd
./Vid2RVID pathof/rvidFrames_folder
```

replacing `pathof/rvidFrames_folder` with the actual folder for the extracted frames folder.

# Compiling

Make sure you have the basic development software installed on your linux environment, then run

```
cd pc
bash compile.sh
```

A static binary executable should be inside the `pc/bin` folder.

# Credits
- [RocketRobz](https://github.com/RocketRobz): original code
- [devkitPro](https://github.com/devkitPro): devkitPro, devkitARM, libnds, and libfat. (DS version)
- [Drenn](https://github.com/Drenn1): GameYob's `.bmp` renderer for (deprecated) DS version.
- [Gericom](https://github.com/Gericom): LZ77 compressor code from EFE/EveryFileExplorer.
