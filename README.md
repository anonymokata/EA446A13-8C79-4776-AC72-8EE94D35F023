# APPARATVS ROMANVS

Implementation of the Roman Numeral Calculator. Depends on the the [Check unit testing framework](https://libcheck.github.io/check/).

## Installation

     $> autoreconf --install
     $> ./configure
     $> make
     $> make check

 ## Docker Container

 A Dockerfile has been included to facilitate running the appplication.

     $> cd docker
     $> docker build -t ubuntu-apparatus .
     $> docker run -it ubuntu-apparatus /bin/bash

## Usage

For addition:

    $> apparatus XI IX
       SVMMA: XX

For subtraction:

    $> apparatus -s XI IX
           SVMMA: II

Chris Baker <ignatz@gmail.com>

# SPQR
