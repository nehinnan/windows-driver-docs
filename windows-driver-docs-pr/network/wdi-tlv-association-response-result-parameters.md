---
title: WDI_TLV_ASSOCIATION_RESPONSE_RESULT_PARAMETERS
author: windows-driver-content
description: WDI_TLV_ASSOCIATION_RESPONSE_RESULT_PARAMETERS is a TLV that contains association response result parameters.
ms.assetid: 8BF2C8B4-207E-479A-9903-3FCDEED5BA2C
ms.author: windowsdriverdev 
ms.date: 0718/2017 
ms.topic: article 
ms.prod: windows-hardware 
ms.technology: windows-devices 
keywords:
 - WDI_TLV_ASSOCIATION_RESPONSE_RESULT_PARAMETERS Network Drivers Starting with Windows Vista
---

# WDI\_TLV\_ASSOCIATION\_RESPONSE\_RESULT\_PARAMETERS


WDI\_TLV\_ASSOCIATION\_RESPONSE\_RESULT\_PARAMETERS is a TLV that contains association response result parameters.

## TLV Type


0x76

## Length


The sum (in bytes) of the sizes of all contained elements.

## Values


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[<strong>WDI_MAC_ADDRESS</strong>](https://msdn.microsoft.com/library/windows/hardware/dn926071)</td>
<td>The MAC address of the peer adapter.</td>
</tr>
<tr class="even">
<td>UINT8</td>
<td>A bit value that indicates whether the request from the peer station is a reassociation request.
<p>Valid values are 0 and 1. A value of 1 indicates that it is a reassociation request.</p></td>
</tr>
<tr class="odd">
<td>UINT8</td>
<td>A bit value that indicates whether the response from the peer station is a reassociation response.
<p>Valid values are 0 and 1. A value of 1 indicates that it is a reassociation response.</p></td>
</tr>
<tr class="even">
<td>[<strong>WDI_AUTH_ALGORITHM</strong>](https://msdn.microsoft.com/library/windows/hardware/dn897792)</td>
<td>The authentication algorithm for the association.</td>
</tr>
<tr class="odd">
<td>[<strong>WDI_CIPHER_ALGORITHM</strong>](https://msdn.microsoft.com/library/windows/hardware/dn897802)</td>
<td>The unicast cipher algorithm for the association.</td>
</tr>
<tr class="even">
<td>[<strong>WDI_CIPHER_ALGORITHM</strong>](https://msdn.microsoft.com/library/windows/hardware/dn897802)</td>
<td>The multicast cipher algorithm for the association.</td>
</tr>
</tbody>
</table>

 

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
<td>Wditypes.hpp</td>
</tr>
</tbody>
</table>

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20WDI_TLV_ASSOCIATION_RESPONSE_RESULT_PARAMETERS%20%20RELEASE:%20%287/10/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


