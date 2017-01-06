# dynamicShader.addLight()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 


## Overview

Add an object which will act as the light source for the Dynamic Shader


## Syntax

	shader.addLight( object )


##### object <small>(required)</small>
_[object]()._ a display object or physics object.  A table with object.x and object.y values can also be used at your own risk.

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.addLight( object )
``````
