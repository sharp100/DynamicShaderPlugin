# shader.setIntensity()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [setAlpha()](setAlpha.markdown), [setZValue()](setZValue.markdown), [setConstant()](setConstant.markdown), [setLinear()](setLinear.markdown), [setQuadratic()](setQuadratic.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Used to set the intensity of the light source added to the [Dynamic Shader](README.md) via [addLight()](addLight.markdown)


## Syntax

	shader.setIntensity( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setIntensity( 0.5 ) -- sets the light intensity for the Dynamic Shader to 50%

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.intensity)
-- OUTPUT: 0.5


``````
