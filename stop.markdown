# shader.stop()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [start()](start.markdown), [destroy()](destroy.markdown), [getEngineState()](getEngineState.markdown)


## Overview

Stops the [Dynamic Shader](README.md) engine

## Syntax

	shader.stop()

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.stop() -- stops the Dynamic Shader engine

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.engine)
-- false


``````
