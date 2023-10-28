# Compositor
This is a simple compositor for the [Wayland](https://wayland.freedesktop.org/) protocol. It is written in C and uses the [wlroots](https://gitlab.freedesktop.org/wlroots/wlroots) library.

## Building
To build the compositor, you need to have the following dependencies installed: `wlroots` and `wayland-protocols`. Then, run `make`.

## Running Compositor
To run the compositor, you need [Wayland](https://wayland.freedesktop.org/). Then, run `./compositor`. Alternatively, you can copy the executable to `/usr/bin` and run `compositor` from anywhere. You could run the Compositor from an X11 session but it is recommended to run it from a TTY.