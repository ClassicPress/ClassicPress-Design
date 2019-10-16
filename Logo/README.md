# ClassicPress logos

The main files are SVG ones.

In the autogenerate folder you'll find automatically converted assets.
You will also be noticed if some file has opened paths.

# Automatic conversion
## Requirements
The conversion is based on **CairoSVG**.
You can install it from command line:
```
$ pip3 install cairosvg
```
and test if there are unsatisfied dependency launching CairoSVG.
```
$ cairosvg
```
*Note: on osX you may have to install cairo and gawk...*
```
$ brew install cairo
$ brew install gawk
```
More information on installation at [CairoSVG](https://cairosvg.org/documentation/).

## Conversion
In the Logo directory:
```
$ . bin/convert-logos.sh
```
