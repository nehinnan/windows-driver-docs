---
title: REMOTE_NDIS_RESET_MSG
description: REMOTE_NDIS_RESET_MSG
ms.assetid: 9cd848c9-85f9-4bc5-bd54-2936270889d4
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# REMOTE\_NDIS\_RESET\_MSG


## <a href="" id="ddk-remote-ndis-reset-msg-ng"></a>


A [**REMOTE\_NDIS\_RESET\_MSG**](https://msdn.microsoft.com/library/windows/hardware/ff570648) message is sent to a Remote NDIS device from a host through the control channel to reset the device and return status. This message may be sent at any time that the device is in a state initialized by Remote NDIS. A reset does not affect Remote NDIS message communication with the host. The device typically resets its network-side controller(s) during this process. A Remote NDIS device will respond to a **REMOTE\_NDIS\_RESET\_MSG** message with a status.

 

 





