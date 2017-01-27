# shader.setPulseTime_down()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See Also__         | [setPulseTime_up()](setPulseTime_up.markdown), [setPulsePause()](setPulsePause.markdown), [setPulseDelay()](setPulseDelay.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Sets the time for the outward pulse


## Syntax

	shader.setPulseTime_down( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1000000

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseTime_down( 2000 ) -- Sets the time for the inward pulse
-- pulse contracts for 2 seconds

``````
