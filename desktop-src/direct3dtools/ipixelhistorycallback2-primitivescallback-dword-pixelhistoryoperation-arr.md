---
Description: A callback that notifies the host of pixel history primitive operation information returned by the associated request.
MS-HAID: vspixengine.IPixelHistoryCallback2\_PrimitivesCallback\_DWORD\_PixelHistoryOperation\_arr
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: IPixelHistoryCallback2::PrimitivesCallback method
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.ipixelhistorycallback2_primitivescallback_dword_pixelhistoryoperation_arr"></span>IPixelHistoryCallback2::PrimitivesCallback method

A callback that notifies the host of pixel history primitive operation information returned by the associated request.

## Syntax


```C++
);
```

## Parameters

*count*   
The number of primitives.

*count0\_primitives*   
The primitives.

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Header</p></td><td>Vspixengine.h</td></tr></tbody></table>

## <span id="see_also"></span>See also

[**IPixelHistoryCallback2**](https://msdn.microsoft.com/library/windows/desktop/mt432736)

 

 


