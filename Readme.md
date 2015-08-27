# jet-color

Implementation of Matlab's Jet color scheme in 256 steps. 

## Description

JET object has properties r, g, b, hex, which are 256-element arrays containing the RGB or hex values for the Jet [color scheme](http://www.mathworks.com/help/matlab/ref/colormap.html).

![picture alt](jet-color.png "16 colors in Jet color scheme. ")

## Usage

`var step = 127;`

`var color = JET.hex[step];`

`var rgb = [JET.r[step], JET.g[step], JET.b[step]];`
