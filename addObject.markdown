# shader.addObject()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __See also__         | [removeObject()](removeObject.markdown)
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)


## Overview

Adds an object to the [Dynamic Shader](README.md).
The object can be a [display object](https://docs.coronalabs.com/api/type/DisplayObject/index.html) or [physics body](https://docs.coronalabs.com/guide/physics/physicsBodies/index.html).

A table named "shader" must be attached to the object before it is added to the [Dynamic Shader](README.md).  This table contains references to the image and normal map file for the object.

## Syntax

	shader.addObject( object )


##### object <small>(required)</small>
a [display object](https://docs.coronalabs.com/api/type/DisplayObject/index.html) or [physics body](https://docs.coronalabs.com/guide/physics/physicsBodies/index.html).

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

-----add shaderInfo table to object------
object.shaderInfo = {  		    -- create the object.shaderInfo table
	name = "object", 	    	-- optional parameter - gives the object a name or the shader will assign one
	map1 = "art/object.png",    -- reference the image file
	map2 = "art/object_n.png"   -- refernece the normal map file
}
-----------------------------------
shader.addObject( object )  -- add object to the Dynamic Shader

shader.start()  -- turn on the Dynamic Shader
``````
