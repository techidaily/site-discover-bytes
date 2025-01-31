---
title: Overcoming Group Policy Constraints on Windows Defender – Your Ultimate 4-Step Solution
date: 2025-01-24T17:40:35.492Z
updated: 2025-01-31T17:33:05.808Z
tags:
  - product
  - antivirus
  - utilities
categories:
  - malwarefox
thumbnail: https://thmb.techidaily.com/30bec39c6c2bfea6784f7fb3989760ee0c9a0b9f3842c193bfea2478974da7cd.jpg
---

## Overcoming Group Policy Constraints on Windows Defender – Your Ultimate 4-Step Solution

With the growing cyber threats, a good security solution is the need of the hour. Windows users have the luxury of a robust security program, **Windows Defender**, which is now known as **Microsoft Defender**. It comes in-built into the latest Windows 10 devices. 

![TotalAv Logo](https://www.malwarefox.com/wp-content/uploads/2024/02/totalav-svg.webp "totalav-svg")

**Stay malware-free with reliable antivirus**

Don't compromise your Data and Privacy. TotalAV is a top-notch antivirus program that handles various viruses, trojans, and other malware that may target your devices. It will safeguard your devices and enhance your system performance.

**4.9**/5

⭐ **Editor's Choice**

✔️ Excellent Malware Detection  
✔️ Multiple set of Features  
✔️ 30 Day Money-Back

[](https://tools.techidaily.com/malwarefox/products/) Get TotalAV > 

Taking lessons from the backlashes it receives after its initial release, Microsoft made some necessary security changes. Today, Microsoft Defender is one of the [top antivirus solutions](https://tools.techidaily.com/malwarefox/products/) in the cybersecurity field and used by millions of users.

However, this extensive security program can malfunction and stop working because of a few errors caused intentionally to stop it; one of those errors is “**Windows Defender blocked by Group Policy**.” 

In this guide, we would list out the possible fixes for this error.

[Is Windows Defender Enough?](https://tools.techidaily.com/malwarefox/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why “Windows Defender blocked by Group Policy” Error Occurs?

There could be a number of reasons for this error to happen. Here are the most common ones.

* Another [third-party antivirus](https://tools.techidaily.com/malwarefox/products/) or antimalware is clashing with the Windows Defender program.
* Cybercriminals might have used infiltrate Group Policy using [malware](https://tools.techidaily.com/malwarefox/products/) to disable the security of the Windows system.
* Some unauthorized changes in the Group Policies can also lead to the error. The changes can be made by mistake or intentionally too.

## How to fix “Windows Defender is Turned off by Group Policy”?

### **Using Group Policy Editor**

**_Note_**_: The Group Policy Editor is not available on the Windows 10 Home version_

1. Search for the **Group Policy Editor** in the windows search bar and launch it.![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. In the editor, navigate to: **Computer Configuration** \-> **Administrative Templates** \-> **Windows Components** \-> **Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Locate “**Turn off Microsoft Defender Antivirus**” and double click on it to open it.![Turn Off Microsoft Defender Antivirus](https://www.malwarefox.com/wp-content/uploads/2020/10/Turn-Off-Microsoft-Defender-Antivirus.png)
4. In order to enable the Microsoft Defender, click on the **Disabled** bullet.![Enable-MS-Defender](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-Defender.png)

5. Click **Apply** and **OK** to finish the configuration.

6. Restart the system to enable the settings.

---

### **Using Registry Editor**

1. Search for “**Registry Editor**” in the windows search box and launch it.![launch registry editor](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-registry-editor.png)
2. Navigate to or copy & paste this path to reach the Windows Defender folder: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click on the **DisableRealTimeMonitoring** key and Delete it.![Delete DisableRealtimeMonitoring key](https://www.malwarefox.com/wp-content/uploads/2020/10/Delete-DisableRealtimeMonitoring-key.png)
4. Exit from the Registry Editor and reboot your system to apply the changes.

---

---

### **Using the PowerShell Command**

1. Search for the **Windows Powershell** in the Windows search box and select **Run as Administrator.**![PowerShell Run as Admin](https://www.malwarefox.com/wp-content/uploads/2020/10/PowerShell-Run-as-Admin.jpg)
2. Type or copy & paste this command and hit the enter key: **_Set-MpPreference -DisableRealtimeMonitoring 0_**![Enable MS defender with Powershell](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-defender-with-Powershell.png)

---

### **Using Windows Settings**

1. Right-click on the windows start icon and choose Settings from the list.![Settings](https://www.malwarefox.com/wp-content/uploads/2020/10/Settings.png)
2. Select **Update & Security** settings.![Update and Security](https://www.malwarefox.com/wp-content/uploads/2020/10/Update-and-Security.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. From the left-pane choose **Windows Security**![launch windows security](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-windows-security.png)

4. Next, click on **Virus & threat protection**.![Choose virus & threat protection](https://www.malwarefox.com/wp-content/uploads/2020/10/Choose-virus-threat-protection.png)
5. Navigate to Virus & threat protection settings and click on **Manage settings**.![manage V&T settings](https://www.malwarefox.com/wp-content/uploads/2020/10/manage-VT-settings.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Toggle the switch to turn on the Microsoft Defender **real-time protection**.![turn On the Real Time protection](https://www.malwarefox.com/wp-content/uploads/2020/10/turn-On-the-RT-protection.png)

---

### **Disable the Third-Party Security App**

The “Windows Defender blocked by Group Policy” error can also be caused if any third-party application has conflicts with the Defender. So, if you really require Windows Defender to run, try disabling the third-party antimalware or antivirus application and then launch the Defender app.

[How to Choose Best Antivirus for Windows 10](https://tools.techidaily.com/malwarefox/products/)

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Final Words

These are the top working solutions to fix the Windows Defender blocked by Group Policy error. If you apply the steps correctly, you would be able to run the Defender application eventually. However, if the problem persists even after trying the above methods, you can get the robust security solutions like **[Malwarefox](https://tools.techidaily.com/malwarefox/products/)**, that can provide better protection than the Microsoft Defender.

**Why my Windows Defender is turned off?** 

Windows Defender on your system can be turned off because of the various reasons like any third-party security app is conflicting with it, or a malware attack has infiltrated and modified the settings to disable it.

**Where is Windows Defender in group policy?** 

To edit the Windows Defender settings in the group policy editor, you can follow this path: **Local Computer Policy > Administrative Templates > Windows Components > Windows Defender Antivirus.** In the latest Windows version, the name of the Windows Defender is changed to **Microsoft Defender.** On those systems, the path to be followed is: **Local Computer Policy > Administrative Templates > Windows Components > Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Leave a Comment [Cancel reply](https://tools.techidaily.com/malwarefox/products/)

Comment

Name Email 

Save my name, email, and website in this browser for the next time I comment.

Δ

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-storytelling-revolution-free-cross-platform-social-sensations/"><u>[New] 2024 Approved Storytelling Revolution FREE, Cross-Platform Social Sensations</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-banishing-unwanted-green-in-mac-recorded-youtube-content/"><u>[New] In 2024, Banishing Unwanted Green in Mac-Recorded YouTube Content</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-from-zero-to-hero-funimates-apk-unleashed-playbook/"><u>[Updated] From Zero to Hero Funimate's APK Unleashed Playbook</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-best-5-gif-to-video-converters-online-no-need-to-download/"><u>[Updated] In 2024, Best 5 GIF to Video Converters Online [No Need to Download]</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/tecra-a50-c/"><u>東芝Tecra A50-C ハードディスク変更手引き</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/complete-step-by-step-manual-on-replacing-the-hard-drive-in-a-toshiba-tecra-a50-c-laptop/"><u>Complete Step-by-Step Manual on Replacing the Hard Drive in a Toshiba Tecra A50-C Laptop</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/guida-rapida-come-risolvere-linstallazione-dellapp-windows-store-che-fallisce-su-windows-11/"><u>Guida Rapida: Come Risolvere L'installazione Dell'app Windows Store Che Fallisce Su Windows 11</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/guide-facile-fabriquer-et-utiliser-une-cle-usb-dinstallation-pour-changer-dordinateur-avec-windows-11/"><u>Guide Facile: Fabriquer Et Utiliser Une Clé USB D'Installation Pour Changer D'Ordinateur Avec Windows 11</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/herstel-van-ontspoord-dll-bestanden-in-windows-11-een-duidelijke-navigatieboodschap-over-13-oplossingen/"><u>Herstel Van Ontspoord DLL-Bestanden in Windows 11: Een Duidelijke Navigatieboodschap Over 13 Oplossingen</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-poco-c55-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Poco C55 Quickly? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-android-alert-personalization-how-to-set-unique-sounds-for-each-app/"><u>Mastering Android Alert Personalization: How to Set Unique Sounds for Each App</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/mastering-vimeo-video-editing-top-5-techniques-for-cuts-and-trimming-for-2024/"><u>Mastering Vimeo Video Editing Top 5 Techniques for Cuts & Trimming for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/must-visit-web-resources-for-text-aesthetics-and-functionality-for-2024/"><u>Must-Visit Web Resources for Text Aesthetics & Functionality for 2024</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/step-by-step-guide-to-flushing-the-cache-on-your-samsung-galaxy-note-10-plus/"><u>Step-by-Step Guide to Flushing the Cache on Your Samsung Galaxy Note 10 Plus</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/tapez-vous-facilement-votre-systeme-dexploitation-windows-11-sur-une-cle-usb-a-laide-du-logiciel-de-sauvegarde-gratuit-le-plus-performant/"><u>Tapez-Vous Facilement Votre Système D'exploitation Windows 11 Sur Une Clé USB À L'aide Du Logiciel De Sauvegarde Gratuit Le Plus Performant</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/understanding-vmware-vcenter-version-updates-key-insights/"><u>Understanding VMware vCenter Version Updates: Key Insights</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-acer-sound-drivers-with-speed-a-simple-guide/"><u>Update Your Acer Sound Drivers with Speed: A Simple Guide</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/1728496421475-windows-1110/"><u>Windows 11/10文件拷贝找回技巧必看教程</u></a></li>
</ul></div>

