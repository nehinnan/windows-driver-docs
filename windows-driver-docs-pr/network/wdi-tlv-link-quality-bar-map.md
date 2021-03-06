---
title: WDI_TLV_LINK_QUALITY_BAR_MAP
author: windows-driver-content
description: WDI_TLV_LINK_QUALITY_BAR_MAP is a TLV that contains the mapping of signal quality to Wi-Fi signal strength bars.
ms.assetid: 35E073F4-D372-466A-98FF-0AAB1695284E
ms.author: windowsdriverdev 
ms.date: 0718/2017 
ms.topic: article 
ms.prod: windows-hardware 
ms.technology: windows-devices 
keywords:
 - WDI_TLV_LINK_QUALITY_BAR_MAP Network Drivers Starting with Windows Vista
---

# WDI\_TLV\_LINK\_QUALITY\_BAR\_MAP


WDI\_TLV\_LINK\_QUALITY\_BAR\_MAP is a TLV that contains the mapping of signal quality to Wi-Fi signal strength bars.

## TLV Type


0xD8

## Length


The size (in bytes) of the array of WDI\_LINK\_QUALITY\_BAR\_MAP\_PARAMETERS elements. The array must contain 1 or more elements.

**Note**  WDI\_LINK\_QUALITY\_BAR\_MAP\_PARAMETERS is not a WDI structure. It is defined in the WDI TLV parser generator, and is used for documentation purposes only.

 

## Values


| Type                                         | Description                                         |
|----------------------------------------------|-----------------------------------------------------|
| WDI\_LINK\_QUALITY\_BAR\_MAP\_PARAMETERS\[\] | An array of signal strength bar mapping parameters. |

 

WDI\_LINK\_QUALITY\_BAR\_MAP\_PARAMETERS consists of the following elements.

| Type  | Description                                                                  |
|-------|------------------------------------------------------------------------------|
| UINT8 | The lower limit link quality (0-100) for the current signal strength bar.    |
| UINT8 | The upper limit of link quality (0-100) for the current signal strength bar. |
| UINT8 | The signal strength bar number.                                              |

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 10</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2016</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td>Dot11wdi.h</td>
</tr>
</tbody>
</table>

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20WDI_TLV_LINK_QUALITY_BAR_MAP%20%20RELEASE:%20%287/10/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


