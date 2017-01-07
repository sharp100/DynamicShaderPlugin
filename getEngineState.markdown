# shader.getEngineState()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [start()](start.markdown), [stop()](stop.markdown), [destroy()](destroy.markdown)


## Overview

Shortcut to engine value (true or false)

## Syntax

	shader.getEngineState()
  __*returns*__ true or false
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local engine = shader.getEngineState() -- returns engine state

print(engine)
-- OUTPUT: true


``````
