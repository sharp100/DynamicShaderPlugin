# shader.removeLight()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [addLight()](addLight.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Removes the current light source for the [Dynamic Shader](README.md).  The light source is set to the default location (0, 0) until a new light source ia added to the [Dynamic Shader](README.md) via [addLight()](addLight.markdown).


## Syntax

	shader.removeLight()

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.removeLight()
``````
