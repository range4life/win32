---
Description: 'Specifies whether 2-channel audio is encoded as stereo or dual mono.'
ms.assetid: '37f25590-69c2-43bd-a5d4-2262457cb39d'
title: AVEncAudioDualMono property
---

# AVEncAudioDualMono property

Specifies whether 2-channel audio is encoded as stereo or dual mono.

This property is read/write.

## Data type

**UINT32** (**VT\_UI4**)

## Property GUID

**CODECAPI\_AVEncAudioDualMono**

## Property value

The value of this property is a member of the [**eAVEncAudioDualMono**](eavencaudiodualmono.md) enumeration.

## Remarks

This property does not apply to MPEG audio encoders. For MPEG audio, use the [**AVEncMPACodingMode**](avencmpacodingmode-property.md) property.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�2000 Professional \[desktop apps \| UWP apps\]<br/>                     |
| Minimum supported server<br/> | Windows�2000 Server \[desktop apps \| UWP apps\]<br/>                           |
| Header<br/>                   | <dl> <dt>Codecapi.h</dt> </dl> |



## See also

<dl> <dt>

[Codec API Properties](codec-api-properties.md)
</dt> <dt>

[**ICodecAPI Interface**](icodecapi.md)
</dt> </dl>

�

�



