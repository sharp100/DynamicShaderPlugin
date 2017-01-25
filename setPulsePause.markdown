# shader.setPulsePause()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See Also__         | [setPulseTime_up()](setPulseTime_up.markdown), [setPulseTime_down()](setPulseTime_down.markdown), [setPulseDelay()](setPulseDelay_down.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Pauses between the outward pulse and the inward pulse


## Syntax

	shader.setPulsePause( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1000000

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulsePause( 2000 ) -- Sets a pause between the pulse up and the pulse down.
-- 2 second pause between the outward and inward pulse

``````
