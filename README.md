# tutorials
a collection of minimal example programs forked from https://github.com/eyelash/tutorials/tree/master/wayland-compositor


compile with the following command:

gcc -o wayland-compositor wayland-compositor.c backend-x11.c xdg-shell.c -lwayland-server -lX11 -lEGL -lGL -lX11-xcb -lxkbcommon-x11 -lxkbcommon
