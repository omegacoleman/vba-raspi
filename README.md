
# vba-raspi

This is modified by coleman<1305381973@qq.com> from the [Legacy VisualBoyAdvance](https://sourceforge.net/projects/vba) source code which is written back in 2004. Works on the latest (2017-9-6) raspbian and should also work for other linux-based boards. 

In fact, it should work on any of the modern Linux system, if you want to play games stretched to fullscreen using the powerful coleman\_stretcher (see src/sdl/SDL.cpp).

Notice: it is required that you have a screen with modern resolution (bigger than 400x300 likely).

# INSTALL

`
CFLAGS=-O2 -fpermissive CXXFLAGS=-O2 -fpermissive ./configure
make
sudo make install
`

