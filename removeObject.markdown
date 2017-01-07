# shader.removeObject()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [addObject()](addObject.markdown)


## Overview

Removes an object from the [Dynamic Shader](README.md).

## Syntax

	shader.removeObject( object )


##### object <small>(required)</small>
a [display object](https://docs.coronalabs.com/api/type/DisplayObject/index.html) or [physics body](https://docs.coronalabs.com/guide/physics/physicsBodies/index.html).

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.removeObject( object )  -- add object to the Dynamic Shader

``````
