# shader.addObject()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [removeObject()](removeObject.markdown)


## Overview

Adds an object to the Dynamic Shader.
The object can be a [display object](https://docs.coronalabs.com/api/type/DisplayObject/index.html) or [physics body](https://docs.coronalabs.com/guide/physics/physicsBodies/index.html).

A table named "shader" must be attached to the object before it is added to the Dynamic Shader.  This table contains references to the image and normal map file for the object.

## Syntax

	shader.addObject( object )


##### object <small>(required)</small>
a [display object](https://docs.coronalabs.com/api/type/DisplayObject/index.html) or [physics body](https://docs.coronalabs.com/guide/physics/physicsBodies/index.html).

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'
-----add object.shader table------
pug.shader = {}
pug.shader.name = "pug_shader"
pug.shader.map1 = "art/pug.png"
pug.shader.map2 = "art/pug_n_white.png"
-----------------------------------
shader.addObject( object )
``````
