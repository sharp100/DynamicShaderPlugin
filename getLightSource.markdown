# shader.getLightSource.markdown()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | object
| __Keywords__         | 
| __See also__         | 



## Overview

Returns the Dynamic Shaader object assigned as the light source via [setLightColor()](setLightColor.markdown)


## Syntax

	shader.getLightSource( )
  
  _*returns*_ object assigned as the light source via [setLightColor()](setLightColor.markdown)
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

-- example with no return value
shader.getLightSource( )

-- example with return value
local lightSource = shader.getLightSource( )

``````
