# Ruthen1um's build of st

My `st` build is very raw so use it at your own risk.
This file will be updated as soon as new features appear.

## Installation

The original `st` can be downloaded from
[the official suckless site](https://st.suckless.org/).

### Requirements

In order to build `st` you need the `Xlib` header files.

### Steps

1. Clone
[this repository](https://github.com/Ruthen1um/st)
somewhere (`st` used as an example):
```shell
git clone https://github.com/Ruthen1um/st.git st
```

2. `cd` to the cloned repo:
```shell
cd st
```

3. Build `st` using `make`:
```shell
sudo make clean install
```

### Features

- Wide glyphs support with
[this patch](https://st.suckless.org/patches/glyph_wide_support/)
