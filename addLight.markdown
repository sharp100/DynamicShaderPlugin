# shader.addLight()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | 
| __Keywords__         | 
| __See also__         | [removeLight()](removeLight.markdown)


## Overview

Add an object which will act as the light source for the [Dynamic Shader](README.md).  The object will replace a previously added light.


## Syntax

	shader.addLight( object )


##### object <small>(required)</small>
_[object]()._ a display object or physics object.  A table with object.x and object.y values can also be used at your own risk.

### NOTE
The [Dynamic Shader](README.md) will attach a table named __shaderInfo__ to the object.
The table can be ignored if you plan to move the light source using only one method. However, you might find the __object.shaderInfo.available__ value helpful as an on-off toggle if you plan to move the light source with more than one method, e.g. following a touch event, following a touchjoint or moving with a transistion or translate command.
``````lua
-- The Dynamic Shader adds shaderInfo table
object.shaderInfo = {
	name = "I am the light source!", -- gives the the light source a name and
	available = true
}
-- creates an "available" value.  This will be helpful if you plan to move
-- the light source with more than one method, e.g. following a touch event, following a touchjoint
-- or moving with a transistion or translate command.
``````

## Examples

``````lua
local shader = require 'plugin.dynamic-shader'

shader.addLight( object )
``````
