# shader.setDebugLevel()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | 

## Overview

Sets the level of Dynamic Shader debug information returned to the console via [print()](https://docs.coronalabs.com/api/library/global/print.html) functions


## Syntax

	shader.setDebugLevel( number )

[number](https://docs.coronalabs.com/api/type/Number.html) is a value between 0 and 2

- 0 = no reporting
- 1 = report major events
- 2 = report all 


## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.setDebugLevel( 0 ) -- no debug messaging
shader.setDebugLevel( 1 ) -- [print()](https://docs.coronalabs.com/api/library/global/print.html) all debug messages to the console
shader.setDebugLevel( 2 ) -- [print()](https://docs.coronalabs.com/api/library/global/print.html) all debug messages to the console



``````
