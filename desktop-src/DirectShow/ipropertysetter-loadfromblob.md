---
description: The LoadFromBlob method loads property data from a persistence format.
ms.assetid: b314a844-2190-469a-a030-4494e2140ce6
title: IPropertySetter::LoadFromBlob method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IPropertySetter.LoadFromBlob
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IPropertySetter::LoadFromBlob method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `LoadFromBlob` method loads property data from a persistence format.

## Syntax


```C++
HRESULT LoadFromBlob(
  [in] LONG cSize,
  [in] BYTE *pb
);
```



## Parameters

<dl> <dt>

*cSize* \[in\]
</dt> <dd>

Size of the data, in bytes.

</dd> <dt>

*pb* \[in\]
</dt> <dd>

Pointer to an array of bytes that contains the data.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://msdn.microsoft.com/windowsvista/bb980924.aspx). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IPropertySetter Interface**](ipropertysetter.md)
</dt> <dt>

[Error and Success Codes](error-and-success-codes.md)
</dt> </dl>

 

 




