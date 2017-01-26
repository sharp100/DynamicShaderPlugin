# shader.setPulseDelay()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See Also__         | [setPulseTime_up()](setPulseTime_up.markdown), [setPulseTime_down()](setPulseTime_down.markdown), [setPulsePause()](setPulsePause.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Sets the delay between pulse cycles (pulse cycle 1 . . . __delay__ . . . pulse cycle 2, etc.)


## Syntax

	shader.setPulseDelay( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 1000000

## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

shader.setPulseDelay( 2000 ) -- Sets the time delay between pulse cycles
-- 2 second delay between pulse cycles

``````
