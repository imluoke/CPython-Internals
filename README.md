# Cpython Internals

* [简体中文](https://github.com/zpoint/CPython-Internals/blob/master/README_CN.md)
* **watching** this repo so that you will be notified when there's update

This repository is my notes/blog for [cpython](https://github.com/python/cpython) source code

Trying to illustrate every detail of cpython implementation

    # based on version 3.8.0a0
    cd cpython
    git reset --hard ab54b9a130c88f708077c2ef6c4963b632c132b3


### Table of Contents

* [Objects](#Objects)
* [Modules](#Modules)
* [Lib](#Lib)
* [Interpreter](#Interpreter)
* [learning material](#learning-material)


#### Objects
 - [x] [dict](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/dict/dict.md)
 - [x] [long/int](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/long/long.md)
 - [x] [unicode/str](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/str/str.md)
 - [x] [set](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/set/set.md)
 - [x] [list](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/list/list.md)
 - [x] [tuple](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/tuple/tuple.md)
 - [x] [bytes](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/bytes/bytes.md)
 - [x] [bytearray](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/bytearray/bytearray.md)
 - [x] [float](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/float/float.md)
 - [x] [func(user-defined method)](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/func/func.md)
 - [x] [method(builtin method)](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/method/method.md)
 - [x] [iter](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/iter/iter.md)
 - [x] [gen](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/gen/gen.md)
 - [x] [class(bound method/classmethod/staticmethod)](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/class/class.md)
 - [x] [complex](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/complex/complex.md)
 - [x] [enum](https://github.com/zpoint/CPython-Internals/blob/master/BasicObject/enum/enum.md)

#### Modules

 - [ ] io
 	- [x] [fileio](https://github.com/zpoint/CPython-Internals/blob/master/Modules/io/fileio/fileio.md)

#### Lib

 - [x] [re](https://github.com/zpoint/CPython-Internals/blob/master/Modules/re/re.md)
 - [ ] asyncio

#### Interpreter

 - [ ] [frame](https://github.com/zpoint/CPython-Internals/blob/master/Interpreter/frame/frame.md)
 - [ ] code
 - [ ] descr
 - [ ] exception
 - [ ] module
 - [ ] namespace
 - [ ] GIL
 - [ ] gc
 - [ ] memory management

#### learning material

I will only recommend what I've read

* [rushter](https://rushter.com/)
* [YET ANOTHER PYTHON INTERNALS BLOG](https://pythoninternal.wordpress.com/)
* [CPython internals - Interpreter and source code overview](https://www.youtube.com/watch?v=LhadeL7_EIU&list=PLzV58Zm8FuBL6OAv1Yu6AwXZrnsFbbR0S)
* [< < Inside The Python Virtual Machine > >](https://leanpub.com/insidethepythonvirtualmachine)
* [< < Python源码剖析 > >](https://book.douban.com/subject/3117898/)