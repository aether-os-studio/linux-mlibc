# linux-mlibc

Attempt at creating a [mlibc](https://github.com/managarm/mlibc)-based Linux distribution.

Derived and restructured from [czapek1337's patches](https://github.com/czapek1337/linux-mlibc).

## Build instructions

```shell
$ mkdir build && cd $_ # create and cd into a build directory
$ xbstrap init ../ # init xbstrap with the source directory containing bootstrap.yml
$ xbstrap install -u weston # build weston
```
