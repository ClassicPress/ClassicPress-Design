# ClassicPress logos

The main files are SVG ones.

# Automatic conversion

In the autogenerate folder you'll find automatically converted assets.

The script checks that:

- the paths are closed;
- SVG title is file name (without extension).

## Conversion
In the Logo directory source the script:
```
$ . bin/generate-assets.sh
```

## Requirements

### The conversion script uses *InkScape*.
You can find the latest InkScape version [here](https://inkscape.org/it/).

### OsX notes
- You may have to install cairo and gawk.
- Make sure `/Applications/Inkscape.app/Contents/Resources/bin/` is in your path.


