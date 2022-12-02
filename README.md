# x264-r2727
x264 r2727 w/ mbtree overhead fix

Build instructions:

1) Get MSYS2.
2) Get VS 2015 build tools.
3) Run MSYS2 MSYS.
4) Clone repository.
5) Run VS2015 x64 Native Tools Command Prompt.
6) Navigate into MSYS2 install directory.
7) msys2_shell.cmd -mingw64 -use-full-path
8) Navigate into repo clone in mingw64 window.
9) CC=cl ./configure --enable-static --prefix=${PWD}/installed
10) make
11) make install

If you've done everything correctly, x264.exe will be dropped into RepositoryClone/installed/bin
