# xkbcomp-feedstock

Feedstock for building the xkbcomp conda package for Anaconda main channel.

## About xkbcomp

The X Keyboard (XKB) Compiler compiles XKB keyboard description files into 
formats usable by the X server or client libraries. This tool is essential 
for X11 keyboard configuration and is required by Xvfb and other X servers 
for keyboard initialization.

## Building

```bash
conda build recipe/
```

## Testing

The package includes basic tests to verify:
- The xkbcomp binary is installed
- The binary runs and displays help output

