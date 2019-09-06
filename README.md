# Linux.Fe2O3

This is a POC ELF prepender written in Rust. I like writting prependers on languages that I'm learning and find interesting. As for the name, `Fe2O3` is the chemical formula of Rust, I thought it was appropriate.

# Build
```$ cd src
$ rustc main.rs -o Linux.Fe2O3
```

Note that the Rust version used is `rustc 1.37.0 (eae3437df 2019-08-13)`, the latest at this moment.

# Binary Sample
A binary sample is also available at https://www.guitmz.com/Linux.Fe2O3 

```
$ file Linux.Fe2O3
Linux.Fe2O3: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 3.2.0, with debug_info, not stripped

$ sha1sum Linux.Fe2O3
c185ab0fd9b1c8f3ddaed7079898383edbcbb7f7  Linux.Fe2O3
```

# Demo
[![asciicast](https://asciinema.org/a/gMwAoQozAKpX851zXE8DncDSc.png)](https://asciinema.org/a/gMwAoQozAKpX851zXE8DncDSc)
