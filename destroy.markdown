# shader.destroy()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [start()](start.markdown), [stop()](stop.markdown), [getEngineState()](getEngineState.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Removes all objects from the [Dynamic Shader](README.md) and stops the Dynamic Shader engine.

## Syntax

	shader.destroy()

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.destroy() -- removes all objects from the Dynamic Shader and stops the Dynamic Shader engine

local lightTable = shader.getLightTable() -- get the current Dynamic Shader values

print(lightTable.engine)
-- false

local objectList = shader.getObjectList()

print(objectList)
-- empty table


``````
