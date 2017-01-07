# shader.setLinear()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [setAlpha()](setAlpha.markdown), [setIntensity()](setIntensity.markdown), [setZValue()](setZValue.markdown), [setConstant()](setConstant.markdown), [setQuadratic()](setQuadratic.markdown)


## Overview

Used to set the [linear](https://developer.valvesoftware.com/wiki/Constant-Linear-Quadratic_Falloff#Linear_Attenuation) value for light attenuation in the Dynamic Shader's [1 Point Light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight) setting.
The [light attenuation](https://developer.valvesoftware.com/wiki/Constant-Linear-Quadratic_Falloff) table consists of three values {constant, linear, quadratic}
The ratio of the 3 values modifies the behavior of light in the Dynamic Shader's [1 Point Light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight).

__Not used with__  [directional light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight)


## Syntax

	shader.setLinear( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setLinear( 0.5 ) -- sets the "linear" value for light attenuation in the Dynamic Shader's 1 Point Light setting

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.linear)
-- 0.5


``````
