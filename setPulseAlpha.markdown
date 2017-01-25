# shader.setPulseAlpha()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [setPulseAlpha()](setPulseAlpha.markdown), [setPulseIntensity()](setPulseIntensity.markdown), [setPulseZValue()](setPulseZValue.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Determines whether or not the Dynamic Shader's alpha is reactive to the pulse


## Syntax

	shader.setPulseAlpha( boolean )

[boolean value](https://docs.coronalabs.com/api/type/Boolean.html)
 - true  : The Dynamic Shader's alpha value will react to the pulse
 - false : The Dynamic Shader's alpha value will __NOT__ react to the pulse

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseAlpha( true ) -- The Dynamic Shader's alpha value will react to the pulse

shader.setPulseAlpha( false ) -- The Dynamic Shader's alpha value will NOT react to the pulse


``````
