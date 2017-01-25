# shader.setPulseAlpha()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Pulse Alpha__      | [setPulseAlpha_up()](setPulseAlpha_up.markdown), [setPulseAlpha_down()](setPulseAlpha_down.markdown)
| __Pulse Intensity__  |[setPulseIntensity()](setPulseIntensity.markdown), [setPulseIntensity_up()](setPulseIntensity_up.markdown), [setPulseIntensity_down()](setPulseIntensity_down.markdown)
| __Pulse zValue__     |[setPulseZValue()](setPulseZValue.markdown), [setPulseZValue_up()](setPulseZValue_up.markdown), [setPulseZValue_down()](setPulseZValue_down.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Determines if the Dynamic Shader's alpha is reactive to the pulse or not


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
