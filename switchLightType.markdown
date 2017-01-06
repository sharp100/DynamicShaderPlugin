# shader.switchLightType()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | lightType, lightTypeName
| __Keywords__         | 
| __See also__         | 



## Overview

Switches between [directional light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight) and [1 point light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight).


## Syntax

	shader.switchLightType( )
  
  _*returns*_ lightType, lightTypeName
  
  - lightType = ["composite.normalMapWith1DirLight"](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight) or ["composite.normalMapWith1PointLight"](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight)
  - lightTypeName = ["directional light"](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight) or ["1 point light"](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight)
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

-- example with no return values
shader.switchLightType( )

-- example with return values
local lightType, lightTypeName = shader.switchLightType( )

``````
