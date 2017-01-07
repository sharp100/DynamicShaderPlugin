# shader.setDebugLevel()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | [number](https://docs.coronalabs.com/api/type/Number.html)
| __Keywords__         | 
| __See also__         | [setDebugLevel()](setDebugLevel.markdown)

## Overview

Returns the current debug level of the [Dynamic Shader](README.md)


## Syntax

	shader.getDebugLevel()

--returns-- a [number](https://docs.coronalabs.com/api/type/Number.html) between 0 and 2

- 0 = no debug messages print() to console
- 1 = major debug messages print() to console
- 2 = all debug messages print() to console


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

local debug = shader.getDebugLevel()
print(debug)
-- OUTPUT: 0 -- default value



``````
