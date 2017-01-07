# shader.setDebugLevel()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 

## Overview

Sets the level of Dynamic Shader debug information returned to the console via [print()](https://docs.coronalabs.com/api/library/global/print.html) functions


## Syntax

	shader.setDebugLevel( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 2


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setIntensity( 0.5 ) -- sets the light intensity for the Dynamic Shader to 50%

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.intensity)
-- 0.5


``````
