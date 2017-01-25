# shader.setPulseZValue_down()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Pulse Alpha__      | [setPulseAlpha()](setPulseAlpha.markdown), [setPulseAlpha_up()](setPulseAlpha_up.markdown), [setPulseAlpha_down()](setPulseAlpha_down.markdown)
| __Pulse Intensity__  |[setPulseIntensity()](setPulseIntensity.markdown), [setPulseIntensity_up()](setPulseIntensity_up.markdown), [setPulseIntensity_down()](setPulseIntensity_down.markdown)
| __Pulse zValue__     |[setPulseZValue()](setPulseZValue.markdown), [setPulseZValue_up()](setPulseZValue_up.markdown), [setPulseZValue_down()](setPulseZValue_down.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Sets the minimum zValue of the pulse


## Syntax

	shader.setPulseZValue_down( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseZValue_down( 0.25 ) -- Sets the minimum zValue of the pulse
-- pulse zValue bottoms out at 0.25

``````
