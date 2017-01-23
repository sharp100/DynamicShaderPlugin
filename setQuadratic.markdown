# shader.setQuadratic()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [setAlpha()](setAlpha.markdown), [setIntensity()](setIntensity.markdown), [setZValue()](setZValue.markdown), [setConstant()](setConstant.markdown), [setLinear()](setLinear.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Used to set the [quadratic](https://developer.valvesoftware.com/wiki/Constant-Linear-Quadratic_Falloff#Quadratic_Attenuation) value for light attenuation in the [Dynamic Shader's](README.md) [1 Point Light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight) setting.
The [light attenuation](https://developer.valvesoftware.com/wiki/Constant-Linear-Quadratic_Falloff) table consists of three values {constant, linear, quadratic}
The ratio of the 3 values modifies the behavior of light in the [Dynamic Shader's](README.md) [1 Point Light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight).

__Not used with__  [directional light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight)


## Syntax

	shader.setQuadratic( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setQuadratic( 0.5 ) -- sets the "quadratic" value for light attenuation in the Dynamic Shader's 1 Point Light setting

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.quadratic)
-- OUTPUT: 0.5


``````
