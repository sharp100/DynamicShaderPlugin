# shader.start()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [stop()](stop.markdown), [destroy()](destroy.markdown), [getEngineState()](getEngineState.markdown)


## Overview

Starts the Dynamic Shader engine

## Syntax

	shader.start()

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.start() -- starts the Dynamic Shader engine

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.engine)
-- true


``````
