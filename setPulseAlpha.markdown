# shader.setPulseAlpha()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [setPulseAlpha()](setPulseAlpha.markdown), [setPulseIntensity()](setPulseIntensity.markdown), [setPulseZValue()](setPulseZValue.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Used to turn the pulse alpha trait on and off.


## Syntax

	shader.setPulseAlpha( boolean )

[boolean](https://docs.coronalabs.com/api/type/Boolean.html) value representing 
 - true  : The Dynamic Shader's alpha value will be reactive to the pulse
 - false : The Dynamic Shader's alpha value will __NOT__ be reactive to the pulse

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseAlpha( true ) -- The Dynamic Shader's alpha value will be reactive to the pulse

shader.setPulseAlpha( false ) -- The Dynamic Shader's alpha value will NOT be reactive to the pulse


``````
