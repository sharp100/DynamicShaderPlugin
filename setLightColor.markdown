# PLUGIN_NAME.FUNCTION()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 


## Overview

Used to set the color of the light source added to the Dynamic Shader via [addLight()](addLight.markdown)


## Syntax

	shader.setLightColor( table )

##### table <small>(required)</small>
_[Table](http://docs.coronalabs.com/api/type/Table.html)_  A table with RGB values


### Format for `table`
  table = {r, g, b}

  - r = red value (0 to 1)
  - g = green value (0 to 1)
  - b = red value (0 to 1)
  
  *alpha values are set by* [setAlpha()](setAlpha.markdown)


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setLightColor( table )
``````
