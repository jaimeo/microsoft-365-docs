---
title: "Create and edit AutoPilot profiles"
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
ms.assetid: 5cf7139e-cfa1-4765-8aad-001af1c74faa
description: "Learn to create, edit, delete, or remove AutoPilot profiles. "
---

# Create and edit AutoPilot profiles

## Create a profile

A profile applies to a device, or a group of devices,
  
1. In the Microsoft 365 Business Admin center, choose **Devices** \> **AutoPilot**.
  
2. On the **AutoPilot** page, choose the **Profiles** tab \> **Create profile**.
    
3. On the **Create profile** page, enter a name for the profile that helps you identify it, for example Marketing, turn on the setting you want (see [About AutoPilot Profile settings](autopilot-profile-settings.md) for more information), and choose **Save**.
    
    ![Enter name and turn on settings in the Create profile panel.](media/63b5a00d-6a5d-48d0-9557-e7531e80702a.png)
  
### Apply profile to a device

After you create a profile you can apply it to a device or a group of devices. You can pick an existing profile in the [step-by-step guide](add-autopilot-devices-and-profile.md), you can apply it to new devices, or you can replace an existing profile for a device or group of devices. 
  
1. On the **Prepare Windows** page, choose the **Devices** tab. 
    
2. Click the check-box next to a device name and in the **Device** panel, choose a profile from the **Assigned profile** drop-down \> **Save**.
    
    ![In the Device panel, select an Assigned profile to apply it.](media/ed0ce33f-9241-4403-a5de-2dddffdc6fb9.png)
  
## Edit, delete, or remove a profile

Once you've assigned a profile to a device, you can update it, even if you've already given the device to a user. When the device connects to the internet, it downloads the latest version of your profile during the setup process. If the user restores their device to its factory default settings, the device will again download the latest updates to your profile. 
  
### Edit a profile

1. On the **Prepare Windows** page, choose the **Profiles** tab. 
    
2. Click the check-box next to a device name and in the **Profile** panel update any of the available settings \> **Save**.
    
    If you do this before a user connects the device to the internet, then the profile gets applied to the setup process.
    
### Delete a profile

1. On the **Prepare Windows** page, choose the **Profiles** tab. 
    
2. Click the check-box next to a device name and in the **Profile** panel click **Delete profile** \> **Save**.
    
    When you delete a profile, it gets removed from a device or a group of devices it was assigned to.
    
### Remove a profile

1. On the **Prepare Windows** page, choose the **Devices** tab. 
    
2. Click the check-box next to a device name and in the **Device** panel, choose a **None** from the **Assigned profile** drop-down \> **Save**.
    
