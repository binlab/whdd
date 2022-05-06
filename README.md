## WHDD is HDD diagnostic and recovery tool for Linux.

Project home: http://whdd.org
License: GNU GPL v3
Sources: https://github.com/whdd/whdd

### To install, run:
```shell
./build.sh && sudo make install
```

### To compile static build (with linked libraries):

```shell
./build_static.sh
```

Installing deps on CentOS end etc

```shell
yum install cmake gcc gcc-c++
```

Build tested with:
```shell
$ cmake --version
cmake version 2.8.12.2
...
$ gcc --version
gcc (GCC) 4.8.5 20150623 (Red Hat 4.8.5-44)
...
```
and

```shell
$ cmake --version   
cmake version 3.20.5
...
$ gcc --version
gcc (GCC) 11.2.1 20220127 (Red Hat 11.2.1-9)
...
```

