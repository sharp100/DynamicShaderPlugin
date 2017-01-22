# shader.setLightColor()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Used to set the color of the light source added to the [Dynamic Shader](README.md) via [addLight()](addLight.markdown)


## Syntax

	shader.setLightColor( table )

##### table <small>(required)</small>
_[Table](http://docs.coronalabs.com/api/type/Table.html)_ with RGB values


### Format for `table`
  table = {r, g, b}
  - r = red value (0 to 1)
  - g = green value (0 to 1)
  - b = red value (0 to 1)
  
*alpha values are set by* [setAlpha()](setAlpha.markdown)


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local table = {1, 1, 1}
shader.setLightColor( table )
-- sets Dynamic Shader color to white
``````
