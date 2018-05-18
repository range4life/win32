---
title: gluDeleteTess function
description: The gluDeleteTess function destroys a tessellation object.
ms.assetid: '7e1540f7-5e7d-4a3b-8c94-5a6800b17411'
keywords: ["gluDeleteTess function OpenGL"]
topic_type:
- apiref
api_name:
- gluDeleteTess
api_location:
- glu32.dll
api_type:
- DllExport
---

# gluDeleteTess function

The **gluDeleteTess** function destroys a tessellation object.

## Syntax


```C++
void WINAPI gluDeleteTess(
  �GLUtesselator *tess
);
```



## Parameters

<dl> <dt>

*tess* 
</dt> <dd>

The tessellation object to destroy (created with [**gluNewTess**](glunewtess.md)).

</dd> </dl>

## Return value

This function does not return a value.

## Remarks

The **gluDeleteTess** function destroys the indicated tessellation object and frees any memory that it used.

## Requirements



|                                     |                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�2000 Professional \[desktop apps only\]<br/>                           |
| Minimum supported server<br/> | Windows�2000 Server \[desktop apps only\]<br/>                                 |
| Header<br/>                   | <dl> <dt>Glu.h</dt> </dl>     |
| Library<br/>                  | <dl> <dt>Glu32.lib</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Glu32.dll</dt> </dl> |



## See also

<dl> <dt>

[**gluNewTess**](glunewtess.md)
</dt> <dt>

[**gluTessBeginPolygon**](glubeginpolygon.md)
</dt> <dt>

[*gluTessCallback*](glutess.md)
</dt> </dl>

�

�




