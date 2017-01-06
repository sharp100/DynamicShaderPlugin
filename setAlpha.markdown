# shader.setAlpha()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 


## Overview

Used to set the alpha value of the light source added to the Dynamic Shader via [addLight()](addLight.markdown)


## Syntax

	shader.setAlpha( number )

The [number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setAlpha( 0.50 ) -- sets the alpha value for the Dynamic Shader

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values
print(lighTable.alpha)
-- 0.5


``````
