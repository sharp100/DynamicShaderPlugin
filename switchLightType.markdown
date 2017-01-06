# shader.switchLightType()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 



## Overview

Switches between [directional light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1dirlight) and [1 point light](https://docs.coronalabs.com/guide/graphics/effects.html#composite.normalmapwith1pointlight).


## Syntax

	shader.switchLightType( )
  
  returns lightType, lightTypeName
  
  lightType = "composite.normalMapWith1DirLight" or "composite.normalMapWith1PointLight"
  lightTypeName = "directional light" or "1 point light"
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.switchLightType( )

------
local lightType, lightTypeName = shader.switchLightType( )

``````
