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
  
  _*returns*_ a *table* with the current values used by the Dynamic Shader
  
  - table.effect = dirLight, 
  - table.effectName = dirLightName, 
  - table.zValue = 0.5, 
  - table.alpha = 1, 
  - table.color = {1, 1, 1, 1}, 
  table.intensity = 0.5, 
	table.constant = 0.9, 
  table.linear = 0.6, 
  table.quadratic = 0.9, 
  table.engine = false
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local lightTable = shader.getLightTable( )

``````
