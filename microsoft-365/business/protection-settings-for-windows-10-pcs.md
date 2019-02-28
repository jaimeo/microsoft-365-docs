---
title: "Set device protection settings for Windows 10 PCs"
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: bd66c26c-73a4-45a8-8642-3ea4ee7cd89d
description: "Learn about default and other settings available in Microsoft 365 Business to secure Windows 10 devices."
---

# Set device protection settings for Windows 10 PCs

## Secure Windows 10 devices

View a video on how to secure Windows 10 devices with Microsoft 365 Business:
  
> [!VIDEO https://www.microsoft.com/videoplayer/embed/a5734146-620a-4cec-8618-536b3ca37972?autoplay=false]
  
1. Sign in to [Microsoft 365 Business](https://portal.office.com) with global admin credentials. 
    
2. On the left nav, choose **Devices** \> **Policies** \> **Add**.
  
3. On the **Add policy** pane, enter a unique name for this policy. 
    
4. Under **Policy type**, choose **Windows 10 Device Configuration**.
    
5. Expand **Secure Windows 10 Devices** \> configure the settings how you would like. See [Available settings](protection-settings-for-windows-10-pcs.md#bkmk_availablesettings) for more information. 
    
    You can alway use the **Reset default settings** link to return to the default setting. 
    
    ![Add policy pane with Windows 10 Device configuration selected](media/fa9e2dc2-7eae-4c96-af34-765a1f641ecf.png)
  
6. Next decide **Who will get these settings?** If you don't want to use the default **All users** security group, Choose **Change**, search for the security group who will get these settings \> **Select**.
    
7. Finally, choose **Done** to save the policy, and assign it to devices. 
    
## Available settings

By default all settings are **On**. The following settings are available.
  
See [How do protection features in Microsoft 365 Business map to Intune settings](map-protection-features-to-intune-settings.md) for more information. 
  
|||
|:-----|:-----|
|Setting  <br/> |Description  <br/> |
|Help protect PCs from viruses and other threats using Windows Defender Antivirus  <br/> |Requires that Windows Defender Antivirus is turned on to protect PCs from the dangers of being connected to the internet.  <br/> |
|Help protect PCs from web-based threats in Microsoft Edge  <br/> |Turns on settings in Edge that help protect users from malicious sites and downloads.  <br/> |
|Use rules that reduce the attack surface of devices  <br/> |When turned On, attack surface reduction helps block actions and apps typically used by malware to infect devices. This setting is only available if Windows Defender Antivirus is set to On. See [Reduce attack surfaces](https://go.microsoft.com/fwlink/?linkid=870417) to learn more.  <br/> |
|Protect folders from threats such as ransomware  <br/> |This setting uses controlled folder access to protect company data from modification by suspicious or malicious apps, such as ransomware. These types of apps are blocked from making changes in protected folders. This setting is only available if Windows Defender Antivirus is set to On. See [Protect folders with COntrolled folder access](https://go.microsoft.com/fwlink/?linkid=870418) to learn more.  <br/> |
|Prevent network access to potentially malicious content on the Internet  <br/> |Use this setting to block outbound user connections to low-reputation Internet locations that may host phishing scams, exploits or other malicious content. This setting is only available if Windows Defender Antivirus is set to On. See [Protect your network](https://go.microsoft.com/fwlink/?linkid=870419) for more information.  <br/> |
|Help protect files and folders on PCs from unauthorized access with BitLocker  <br/> |Bitlocker protects data by encrypting the computer hard drives and protect against data exposure if a computer is lost or stolen. See [Bitlocker FAQ](https://go.microsoft.com/fwlink/?linkid=871000) for more information.  <br/> |
|Allow users to download apps from Microsoft Store  <br/> |Lets users download and install apps from the Microsoft Store. Apps include everything from games to productivity tools, so we leave this setting **On**, but you can turn it off for extra security.  <br/> |
|Allow users to access Cortana  <br/> |Cortana can be very helpful! She can turn settings on or off for you, give directions, and make sure you're on time for appointments, so we keep this **On** by default.  <br/> |
|Allow users to receive Windows tips and advertisements from Microsoft  <br/> |Windows tips can be handy and help orient users when new features are released.  <br/> |
|Keep Windows 10 devices up to date automatically  <br/> |Makes sure that Windows 10 devices automatically receive the latest updates.  <br/> |
|Turn off device screen when idle for this amount of time  <br/> |Makes sure that company data is protected if a user is idle. A user may be working in a public location, like a coffee shop, and step away or be distracted for just a moment, leaving their device vulnerable to random glances. This setting lets you control how long the user can be idle before the screen shuts off.  <br/> |
   
  

