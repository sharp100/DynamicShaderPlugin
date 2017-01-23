# shader.getEngineState()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | [boolean](https://docs.coronalabs.com/api/type/Boolean.html)
| __See also__         | [start()](start.markdown), [stop()](stop.markdown), [destroy()](destroy.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Returns a [boolean](https://docs.coronalabs.com/api/type/Boolean.html) value representing the state of the [Dynamic Shader](README.md) engine.
 - true = [Dynamic Shader](README.md) is on
 - false = [Dynamic Shader](README.md) if off

## Syntax

	shader.getEngineState()
  __*returns*__ true or false
## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local engine = shader.getEngineState() -- returns engine state (true or false)

print(engine)
-- OUTPUT: true


``````
