---
title: "Create and edit AutoPilot devices"
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: 0f7b1d7c-4086-4331-8534-45d7886f9f34
description: "Learn how to upload devices using AutoPilot in Microsoft 365 Business. You can assign a profile to a device or a group of devices."
---

# Create and edit AutoPilot devices

## Upload a list of devices

You can use the [Step-by-step guide](add-autopilot-devices-and-profile.md) to upload devices, but you can also upload the in the **Devices** tab. 
  
Devices need to meet these requirements:
  
- Windows 10, version 1703 or later.
    
- New devices that have not been through Windows out-of-box experience.

1. In the Microsoft 365 Business Admin center, choose **Devices** \> **AutoPilot** \> **Add**.
  
2. On the **Prepare Windows** page, choose the **Devices** tab \> **Add devices**.
    
    ![In the Devices tab, choose Add devices.](media/6ba81e22-c873-40ad-8a72-ce64d15ea6ba.png)
  
3. On the **Add devices** panel, browse to a [Device list CSV-file](https://support.office.com/article/932e3676-2491-49f0-9177-d893d2f5276e) that you have prepared \> **Save** \> **Close**.
    
    You can get this information from your hardware vendor, or you can use the [Get-WindowsAutoPilotInfo PowerShell script](https://www.powershellgallery.com/packages/Get-WindowsAutoPilotInfo) that will generate a csv file. 
    
## Assign a profile to a device or a group of devices

1. On the **Prepare Windows** page, choose the **Devices** tab and check the check box next to one or more devices. 
    
2. On the **Device** panel, select a profile from the **Assigned profile** drop-down. 
    
    If you don't have any profiles yet, see [Create and edit AutoPilot profiles](create-and-edit-autopilot-profiles.md) for instructions. 
    
