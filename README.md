PyOpenCL
========

Installation of PyOpenCL
-----------------------

1. Check for version of Python.

```bash
Python 3.4.0 (v3.4.0:04f714765c13, Mar 16 2014, 19:25:23) [MSC v.1600 64 bit (AM
D64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

```shell
$ git clone https://github.com/urutu/pyopencl.git
$ cd pyopencl
$ python configure.py \
    --cl-inc-dir=/opencl-install-location/include \
    --cl-lib-dir=/opencl-install-location/lib \
    --cl-libname=OpenCL
$ sudo make install
```
This installs PyOpenCL for Python 3.

Note for Linux Users
--------------

Installing using Python 2
```shell
$ git clone https://github.com/urutu/pyopencl.git
$ cd pyopencl
$ python configure.py \
    --cl-inc-dir=/opencl-install-location/include \
    --cl-lib-dir=/opencl-install-location/lib \
    --cl-libname=OpenCL
$ sudo make install
```

Installing using Python 3
```shell
$ git clone https://github.com/urutu/pyopencl.git
$ cd pyopencl
$ python3 configure.py \
    --cl-inc-dir=/opencl-install-location/include \
    --cl-lib-dir=/opencl-install-location/lib \
    --cl-libname=OpenCL
$ sudo make install
```
