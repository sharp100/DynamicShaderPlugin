# shader.getObjectList()

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [shader.*](README.md)
| __Return value__     | objectList, objectListNames
| __Visual Guide__     | [Visual Guide](http://dynamicshader.com/)



## Overview

Returns a table with all of the objects currently loaded into the [Dynamic Shader](README.md) and a table with only the names of those objects.

## Syntax

	shader.getObjectList( )
  
  __*returns*__ 
  - objectList: a [table](https://docs.coronalabs.com/api/type/Table.html) of all objects loaded to the shader via [addObject()](addObject.markdown) 
  - objectListNames: a [table](https://docs.coronalabs.com/api/type/Table.html) with only the names of the objects from objectList
  
## Examples

``````lua
local shader = require 'plugin.dynamic_shader'

-- example with return values
local objectList, objectListNames = shader.getObjectList( )

print(objectList[1])
-- OUTPUT: object

print(objectListNames[1])
-- OUTPUT: "object name"

``````
