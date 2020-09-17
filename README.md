# About

Survivio is a desktop clone of the popular browser battle royale shooter - surviv.io, written in C++

The project is currently in the stage of early alpha development, so any contribution is welcome.



### Building

1) On Debian and Debian-based linux distributions
    make sure these dependencies (used by SFML library) are satisfied:


        libx11-dev
        libgl1-mesa-dev
        libudev-dev
        libfreetype6-dev
        libopenal-dev
        libflac-dev
        libvorbis-dev
        make
        clang


    (on Mac OS and Windows first step is omitted)

2) clone this repository anywhere:

        git clone https://github.com/Fenex330/Survivio.git

3) In the terminal write:

        mkdir Survivio/build/
        cd Survivio/build/
        cmake .. && make


The folder "bin" inside "build" will contain all the binary files



### Mirror List

Primary https://github.com/Fenex330/Survivio

Secondary https://notabug.org/Fenex33/Survivio