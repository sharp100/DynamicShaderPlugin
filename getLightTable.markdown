# shader.getLightTable()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | [table](https://docs.coronalabs.com/api/type/Table.html)
| __Keywords__         | 
| __See also__         | 



## Overview

Returns a table with the current values used by the [Dynamic Shader](README.md)
__note__ These values are only a snapshot of the moment the method is called.  If any value changes in the [Dynamic Shader](README.md) system, e.g. effect, color, alpha, intensity, zValue, constant, linear, quadratic or engine, then getLightTable() will need to be called again to be accurate.


## Syntax

	shader.getLightTable( )
  
  __*returns*__ a [table](https://docs.coronalabs.com/api/type/Table.html) with the current shading values used by the Dynamic Shader
  
  - table.effect	= [string](https://docs.coronalabs.com/api/type/String.html)
  `"composite.normalMapWith1DirLight" or "composite.normalMapWith1PointLight"`
  - table.effectName	= [string](https://docs.coronalabs.com/api/type/String.html)
  `"directional light" or "1 point light"`
  - table.color		= [table](https://docs.coronalabs.com/api/type/Table.html)
  `table = {red, blue, greed, alpha}` 
  - table.alpha		= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1` 
  - table.intensity	= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1` 
  - table.zValue	= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1`
  - table.constant	= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1`  
  - table.linear	= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1` 
  - table.quadratic	= [number](https://docs.coronalabs.com/api/type/Number.html)
  `a value from 0 to 1` 
  - table.engine	= [Boolean](https://docs.coronalabs.com/api/type/Boolean.html)
  `true = "shader on" , false = "shader off"`
   
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local lightTable = shader.getLightTable( )

print(lightTable.alpha)
-- OUTPUT: 1

print(lightTable.effectName)
-- OUTPUT: "directional light"

print(lightTable.engine)
-- OUTPUT: true

print(lightTable.color[1])
-- OUTPUT: 0.5

``````
