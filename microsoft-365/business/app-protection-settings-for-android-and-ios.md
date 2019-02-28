---
title: "Set app protection settings for Android or iOS devices"
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
ms.assetid: 6f2b80b4-81c3-4714-a7bc-ae69313e8a33
description: "Learn how to create, edit, or delete an app management policy, and protect work files on Android or iOS devices."
---

# Set app protection settings for Android or iOS devices

## Create an app management policy

1. Sign in to [Microsoft 365 Business](https://portal.office.com) with global admin credentials. 
    
2. In the admin center, choose **Devices** \> **Policies** \> **Add policy**.
  
3. On the **Add policy** pane, enter a unique name for this policy. 
    
4. Under **Policy type**, choose **Application Management for Android** or **Application Management for iOS** depending on which set of policies you want to create. 
    
5. Expand **Protect work files when devices are lost or stolen** and **Manage how users access Office files on mobile devices** \> configure the settings how you would like. The **Manage how users access Office files on mobile devices** is **Off** by default, but it is recommended that you turn it **On** and accept the default values. See [Available settings](app-protection-settings-for-android-and-ios.md#bkmk_availablesettings) for more information. 
    
    You can always use the **Reset default settings** link to return to the default setting. 
    
    ![Screenshot of Create a policy with Application management for Android selected](media/eabbe06d-ac0a-4f3a-8630-68c808b1e662.png)
  
6. Next decide **Who will get these settings?** If you don't want to use the default **All Users** security group, choose **Change**, choose the security groups who will get these settings \> **Select**.
    
7. Finally, choose **Done** to save the policy, and assign it to devices. 
    
## Edit an app management policy

1. On the **Policies** card, choose **Edit policy**.
    
2. On the **Edit policy** pane, choose the policy you want to change 
    
3. Choose **Edit** next to each setting to change the values in the policy. When you change a value, it is automatically saved into the policy 
    
4. When you are finished, close the **Edit policy** pane. 
    
## Delete an app management policy

1. On the **Policies** card, choose **Delete policy**.
    
2. On the **Delete policy** pane, choose the policies you want to delete \> **Select**, then **Confirm** to delete the policy or policies you chose. 
    
## Available settings

The following tables give detailed information about the available settings to protect work files on devices and the settings that control how users access Office files from their mobile devices.
  
 See [How do protection features in Microsoft 365 Business map to Intune settings](map-protection-features-to-intune-settings.md) for more information. 
  
### Settings that protect work files

The following settings are available to protect work files if a user's device is lost or stolen:
  
|||
|:-----|:-----|
|Setting  <br/> |Description  <br/> |
|Delete work files from an inactive device after this many days  <br/> |If a device is not used for the number of days that you specify here, any work files stored on the device will automatically be deleted.  <br/> |
|Force users to save all work files to OneDrive for Business  <br/> |If this setting is **On**, the only available save location for work files will be OneDrive for Business.  <br/> |
|Encrypt work files  <br/> |Keep this setting **On** so that work files are protected by encryption. Even if the device is lost or stolen, no one will be able to read your company data.  <br/> |
   
### Settings that control how users access Office files on mobile devices

The following settings are available to manage how users access Office work files:
  
|||
|:-----|:-----|
|Setting  <br/> |Description  <br/> |
|Require a PIN or fingerprint to access Office apps  <br/> |If this settings is **On** users have to provide another form of authentication, in addition to their username and password, before they can use Office apps on their mobile device.  <br/> |
|Reset PIN when login fails this many times  <br/> |To prevent an unauthorized user from randomly guessing a PIN, the PIN will reset after the number of wrong entries that you specify.  <br/> |
|Require users to sign in again after Office apps have been idle for  <br/> |This setting determines how long a user can be idle before they are prompted to sign in again.  <br/> |
|Deny access to work files on jailbroken or rooted devices  <br/> |Clever users may have a device that is jailbroken or rooted. This means that the user can modify the operating system, which can make the device more subject to malware. These devices are blocked when this setting is **On**.  <br/> |
|Allow users to copy content from Office apps into personal apps  <br/> |We do allow this by default, but if the setting is **On**, the user could copy information in a work file to a personal file. If the setting is **Off**, the user will be unable to copy information from a work account into a personal app or personal account.  <br/> |
   

  

