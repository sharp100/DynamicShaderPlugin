# shader.setPulseEasing_up()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See Also __        | [setPulseEasing_down()](setPulseEasing_down.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Sets the [easing functions](https://docs.coronalabs.com/api/library/easing/index.html) of the expanding pulse transitions.
The default setting is __easing.linear__


## Syntax

	shader.setPulseEasing_up( easing.function )

  - easing.linear, easing.continuousLoop, easing.inSine, easing.outSine, easing.inOutSine, easing.outInSine, 
	- easing.inQuad, easing.outQuad, easing.inOutQuad, easing.outInQuad, easing.inCubic, easing.outCubic, 
	- easing.inOutCubic, easing.outInCubic, easing.inQuart, easing.outQuart, easing.inOutQuart, easing.outInQuart,
	- easing.inQuint, easing.outQuint, easing.inOutQuint, easing.outInQuint, easing.inExpo, easing.outExpo, 
	- easing.inOutExpo, easing.outInExpo, easing.inCirc, easing.outCirc, easing.inOutCirc, easing.outInCirc,
	- easing.inBack, easing.outBack, easing.inOutBack, easing.outInBack, easing.inElastic, easing.outElastic, 
	- easing.inOutElastic, easing.outInElastic, easing.inBounce, easing.outBounce, easing.inOutBounce, easing.outInBounce

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseEasing_up( easing.outBack ) -- the easing function "outBack" will be applied to the expanding pulse transitions

``````
