---
title: EM\_PASTESPECIAL message
description: Pastes a specific clipboard format in a rich edit control.
ms.assetid: 'b4b9c1a7-943d-4dc8-bcb9-054c984b82ba'
keywords: ["EM_PASTESPECIAL message Windows Controls"]
topic_type:
- apiref
api_name:
- EM_PASTESPECIAL
api_location:
- Richedit.h
api_type:
- HeaderDef
---

# EM\_PASTESPECIAL message

Pastes a specific clipboard format in a rich edit control.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Specifies the [Clipboard Formats](https://msdn.microsoft.com/library/windows/desktop/ms649013).

</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a [**REPASTESPECIAL**](repastespecial.md) structure or **NULL**. If an object is being pasted, the **REPASTESPECIAL** structure is filled in with the desired display aspect. If *lParam* is **NULL** or the **dwAspect** member is zero, the display aspect used will be the contents of the object descriptor.

</dd> </dl>

## Return value

This message does not return a value.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Richedit.h</dt> </dl> |



## See also

<dl> <dt>

[**REPASTESPECIAL**](repastespecial.md)
</dt> </dl>

�

�




