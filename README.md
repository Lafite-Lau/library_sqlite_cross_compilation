# library_sqlite_cross_compilation
Cross compile SQLITE with powerpc-buildroot-linux-uclibcspe-gcc

Sqlite source code download address: https://www.sqlite.org/download.html

Sqlite version:3.38.5

powerpc-buildroot-linux-uclibcspe-gcc version: gcc version 4.9.3 (Buildroot 2015.08.1) 

Compilation method：
./configure CC=/opt/pu300/host/usr/bin/powerpc-buildroot-linux-uclibcspe-gcc --host=arm-linux  --prefix=/home/vmuser/sqlite3/sqlite
make
make install
