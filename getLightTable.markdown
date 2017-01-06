# shader.getLightTable.markdown()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | table
| __Keywords__         | 
| __See also__         | 



## Overview

Returns a table with the current values used by the Dynamic Shader


## Syntax

	shader.getLightTable( )
  
  *returns* a __table__ with the current values used by the Dynamic Shader
  local dirLight = "composite.normalMapWith1DirLight"
local pointLight = "composite.normalMapWith1PointLight"
local dirLightName = "directional light"
local pointLightName = "1 point light"
  - table.effect = string
  `"composite.normalMapWith1DirLight" or "composite.normalMapWith1PointLight"`
  - table.effectName = string
  `"directional light" or "1 point light"`
  - table.color = table
  `table = {red, blue, greed, alpha}`
  - table.zValue = number
  `a value from 0 to 1` 
  - table.alpha = number
  `a value from 0 to 1` 
  - table.intensity = number
  `a value from 0 to 1` 
  - table.constant = number
  `a value from 0 to 1`  
  - table.linear = number
  `a value from 0 to 1` 
  - table.quadratic = number
  `a value from 0 to 1` 
  - table.engine = Boolean
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local lightTable = shader.getLightTable( )

``````
