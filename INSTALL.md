# Install

## Requirements
CaesiumCLT is based on [libcaesium](https://github.com/Lymphatus/libcaesium) and requires it to be compiled and installed.
Please refer to its own documentation.  
You will also need cmake if you want to compile it from source.

## Instructions

Download the latest release package from [here](https://github.com/Lymphatus/caesium-clt/releases) or clone from git.  
Then run:

    $ cd caesium-clt
    $ mkdir build && cd build
    $ cmake .. -DLIBCAESIUM_PATH=/your/libcaesium/path/dir
    $ make
    $ sudo make install

This will compile and install caesiumclt in your `PATH`.  
You can verify everything went ok by running `caesiumclt -v`.

	