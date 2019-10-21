# ClassicPress logos

The main files are SVG ones.

In the autogenerate folder you'll find automatically converted assets.
You will also be noticed if some file has opened paths.

# Automatic conversion
## Requirements
### The *PNG* conversion is based on *CairoSVG*.
You can install it from command line:
```
$ pip3 install cairosvg
```
and test if there are unsatisfied dependency launching CairoSVG.
```
$ cairosvg
```
More information on installation at [CairoSVG](https://cairosvg.org/documentation/).

### The *EPS* conversion is based on *InkScape*.

### osX notes
- You may have to install cairo and gawk.
```
$ brew install cairo
$ brew install gawk
```
- Make sure `/Applications/Inkscape.app/Contents/Resources/bin/` is in your path.

## Conversion
In the Logo directory source the script:
```
$ . bin/convert-logos.sh
```
