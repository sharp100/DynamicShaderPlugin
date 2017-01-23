# shader.stop()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [start()](start.markdown), [destroy()](destroy.markdown), [getEngineState()](getEngineState.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


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
