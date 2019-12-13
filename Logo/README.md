# ClassicPress logos

The main files are SVG ones.

# Automatic conversion

In the autogenerate folder you'll find automatically converted assets.

The script checks that:

- the paths are closed;
- SVG title is file name (without extension).

It generates raster versions (PNG) for each asset, PDF version and lint the original SVG.

## Conversion
In the Logo directory run the script:
```
$ bin/generate-assets.sh
```

## Requirements

- [InkScape](https://inkscape.org).
- xmllint that is part of [libxml](http://www.xmlsoft.org).

### OsX notes
- Make sure `/Applications/Inkscape.app/Contents/Resources/bin/` is in your path.


