# [Vesper]

by Xaser Acheron (C) 2021

## What The Is This

Vesper is a [MBF21](https://github.com/kraflab/mbf21) weapon mod, serving as a big feature
showcase of all the cool new things DEHACKED can do. This repo contains the source code
used to build the project via [DoomTools](https://github.com/MTrop/DoomTools).

Of particular note is the DECOHack source, used to generate the DEHACKED patch -- check out
the [src/decohack](https://github.com/XaserAcheron/vesper/tree/master/src/decohack) folder
for a working example on how to use DECOHack to build cool new MBF21 things.

Vesper is a [Doomforge](https://hellforgestudios.com/doomforge) release, so big thanks to
Bridgeburner and the folks at [Hellforge Studios](https://hellforgestudios.com)
for hosting n' support n' all that good stuff.

See [wadinfo.txt](https://github.com/XaserAcheron/vesper/blob/master/src/wadinfo.txt) for
more details on the mod itself, supported ports, etc. If you're here, hopefully you're
geeky enough to know what all that jargon means. ;)


## Building the Project

This project is build using the [DoomTools](https://github.com/MTrop/DoomTools) toolchain.
Install it and make sure it's added to your PATH before proceeding, else you won't get far.

For initial setup, clone this project to a new folder and type:

	doommake init


To clean the build folder, type:

	doommake clean


To both initialize and build this project:

	doommake


To build the DeHackEd patch from DECOHack source:

	doommake patch


To build the assets WAD:

	doommake assets


To run this project (after setting the correct properties):

	doommake run


To build all components:

	doommake all


To build the full release and distributable:

	doommake release


Check the `/build` and `/dist` folders next to the project root
for the actual wad itself (xa-vesper.wad or something similar).


## "Binaries"

The latest official release of the WAD itself (the "binary" built from this source)
can be found in one of these places:

- [Project Homepage](https://hellforgestudios.com/doomforge/vesper) at [Doomforge](https://hellforgestudios.com/doomforge)
- [Doomworld Thread](https://www.doomworld.com/forum/topic/123800)

This will be put on /idgames eventually, probably, but not just yet.

If you just wanna play the mod and forget all this building-from-source
nonsense, go there and grab a copy of the wad itself, and have fun!


## License

Code is MIT License. Resources are Whatever(tm).
