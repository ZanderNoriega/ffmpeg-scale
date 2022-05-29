# ffmpeg-scale (v0.1.0)

Convenience wrapper around ffmpeg to scale all images in a directory.

# Requirements

It runs the `ffmpeg` command, so you need to have that installed.

# Usage examples

To resize all files in the current directory (option `-d` to `.`) to width 100 (option `-w` to `100`), while keeping the aspect ratio (setting height, ie. option `-h` to `-1`, as expected by `ffmpeg` for this purpose):

```
$ ffmpeg-scale -w 100 -h -1 -d .
```

# LICENSE

MIT.

tl;dr: Copy, modify, sell, re-sell, etc. Credit me, or don't. I don't care. Just don't blame me for any disasters you cause.

See license file.
