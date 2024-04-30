# Simple Terminal

## Unique features (using dmenu)

+ **follow urls** by pressing `alt-l`
+ **copy urls** in the same way with `alt-y`
+ **copy the output of commands** with `alt-o`

## Bindings 

+ **scrollback** with `alt-↑/↓` or `alt-pageup/down` or `shift` while scrolling the
  mouse.
+ OR **vim-bindings**: scroll up/down in history with `alt-k` and `alt-j`.
  Faster with `alt-u`/`alt-d`.
+ **zoom/change font size**: same bindings as above, but holding down shift as
  well. `alt-home` returns to default
+ **copy text** with `alt-c`, **paste** is `alt-v` or `shift-insert`

## Installation 

You should have xlib header files and libharfbuzz build files installed.

```
git clone https://github.com/duolok/st
cd st
sudo make clean install
```

On OpenBSD, be sure to edit `config.mk` first and remove `-lrt` from the
`$LIBS` before compiling.
