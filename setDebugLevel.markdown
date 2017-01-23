# shader.setDebugLevel()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [getDebugLevel()](getDebugLevel.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)

## Overview

Sets the level of [Dynamic Shader](README.md) debug information returned to the console via [print()](https://docs.coronalabs.com/api/library/global/print.html) functions


## Syntax

	shader.setDebugLevel( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 2

- 0 = no debug messages print() to console
- 1 = major debug messages print() to console
- 2 = all debug messages print() to console


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setDebugLevel( 0 ) -- no debug messaging
shader.setDebugLevel( 1 ) -- major debug messages print() to console
shader.setDebugLevel( 2 ) -- all debug messages print() to console



``````
