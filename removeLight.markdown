# dynamicShader.removeLight()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 


## Overview

Removes the current light source for the Dynamic Shader.  The light source is set to the default location (0, 0) until a [new light source](addLight.markdown) is added to the Dynamic Shader.


## Syntax

	shader.removeLight()

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.removeLight()
``````
