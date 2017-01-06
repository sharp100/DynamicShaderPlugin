# shader.setZValue()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [setAlpha()](setAlpha.markdown), [setIntensity()](setIntensity.markdown), [setConstant()](setConstant.markdown), [setLinear()](setLinear.markdown), [setQuadratic()](setQuadratic.markdown)


## Overview

Used to set the position of the z-axis of the light source added to the Dynamic Shader via [addLight()](addLight.markdown)


## Syntax

	shader.setZValue( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setZValue( 0.5 ) -- sets the position of the z-axis for the light used by the Dynamic Shader

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.zValue)
-- 0.5


``````
