# shader.getLightSource()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | object
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)



## Overview

Returns the [Dynamic Shader](README.md) object assigned as the light source via [setLightColor()](setLightColor.markdown)


## Syntax

	shader.getLightSource( )
  
  _*returns*_ object assigned as the light source via [setLightColor()](setLightColor.markdown)
  
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local lightSource = shader.getLightSource( )

``````
