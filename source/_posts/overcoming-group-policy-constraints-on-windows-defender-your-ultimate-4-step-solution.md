---
title: Overcoming Group Policy Constraints on Windows Defender – Your Ultimate 4-Step Solution
date: 2024-11-02T18:56:59.017Z
updated: 2024-11-06T18:09:18.503Z
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

## Why “Windows Defender blocked by Group Policy” Error Occurs?

There could be a number of reasons for this error to happen. Here are the most common ones.

* Another [third-party antivirus](https://tools.techidaily.com/malwarefox/products/) or antimalware is clashing with the Windows Defender program.
* Cybercriminals might have used infiltrate Group Policy using [malware](https://tools.techidaily.com/malwarefox/products/) to disable the security of the Windows system.
* Some unauthorized changes in the Group Policies can also lead to the error. The changes can be made by mistake or intentionally too.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to fix “Windows Defender is Turned off by Group Policy”?

### **Using Group Policy Editor**

**_Note_**_: The Group Policy Editor is not available on the Windows 10 Home version_

1. Search for the **Group Policy Editor** in the windows search bar and launch it.![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. In the editor, navigate to: **Computer Configuration** \-> **Administrative Templates** \-> **Windows Components** \-> **Microsoft Defender Antivirus**.
3. Locate “**Turn off Microsoft Defender Antivirus**” and double click on it to open it.![Turn Off Microsoft Defender Antivirus](https://www.malwarefox.com/wp-content/uploads/2020/10/Turn-Off-Microsoft-Defender-Antivirus.png)
4. In order to enable the Microsoft Defender, click on the **Disabled** bullet.![Enable-MS-Defender](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-Defender.png)
5. Click **Apply** and **OK** to finish the configuration.

6. Restart the system to enable the settings.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Using Registry Editor**

1. Search for “**Registry Editor**” in the windows search box and launch it.![launch registry editor](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-registry-editor.png)
2. Navigate to or copy & paste this path to reach the Windows Defender folder: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Right-click on the **DisableRealTimeMonitoring** key and Delete it.![Delete DisableRealtimeMonitoring key](https://www.malwarefox.com/wp-content/uploads/2020/10/Delete-DisableRealtimeMonitoring-key.png)
4. Exit from the Registry Editor and reboot your system to apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

---

### **Using the PowerShell Command**

1. Search for the **Windows Powershell** in the Windows search box and select **Run as Administrator.**![PowerShell Run as Admin](https://www.malwarefox.com/wp-content/uploads/2020/10/PowerShell-Run-as-Admin.jpg)
2. Type or copy & paste this command and hit the enter key: **_Set-MpPreference -DisableRealtimeMonitoring 0_**![Enable MS defender with Powershell](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-defender-with-Powershell.png)

---

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Using Windows Settings**

1. Right-click on the windows start icon and choose Settings from the list.![Settings](https://www.malwarefox.com/wp-content/uploads/2020/10/Settings.png)
2. Select **Update & Security** settings.![Update and Security](https://www.malwarefox.com/wp-content/uploads/2020/10/Update-and-Security.png)
3. From the left-pane choose **Windows Security**![launch windows security](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-windows-security.png)

4. Next, click on **Virus & threat protection**.![Choose virus & threat protection](https://www.malwarefox.com/wp-content/uploads/2020/10/Choose-virus-threat-protection.png)
5. Navigate to Virus & threat protection settings and click on **Manage settings**.![manage V&T settings](https://www.malwarefox.com/wp-content/uploads/2020/10/manage-VT-settings.png)

6. Toggle the switch to turn on the Microsoft Defender **real-time protection**.![turn On the Real Time protection](https://www.malwarefox.com/wp-content/uploads/2020/10/turn-On-the-RT-protection.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### **Disable the Third-Party Security App**

The “Windows Defender blocked by Group Policy” error can also be caused if any third-party application has conflicts with the Defender. So, if you really require Windows Defender to run, try disabling the third-party antimalware or antivirus application and then launch the Defender app.

[How to Choose Best Antivirus for Windows 10](https://tools.techidaily.com/malwarefox/products/)

---

## Final Words

These are the top working solutions to fix the Windows Defender blocked by Group Policy error. If you apply the steps correctly, you would be able to run the Defender application eventually. However, if the problem persists even after trying the above methods, you can get the robust security solutions like **[Malwarefox](https://tools.techidaily.com/malwarefox/products/)**, that can provide better protection than the Microsoft Defender.

**Why my Windows Defender is turned off?** 

Windows Defender on your system can be turned off because of the various reasons like any third-party security app is conflicting with it, or a malware attack has infiltrated and modified the settings to disable it.

**Where is Windows Defender in group policy?** 

To edit the Windows Defender settings in the group policy editor, you can follow this path: **Local Computer Policy > Administrative Templates > Windows Components > Windows Defender Antivirus.** In the latest Windows version, the name of the Windows Defender is changed to **Microsoft Defender.** On those systems, the path to be followed is: **Local Computer Policy > Administrative Templates > Windows Components > Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-2023-assessment-of-apeaksofts-pioneering-screens-recording/"><u>[New] 2024 Approved The 2023 Assessment of Apeaksoft's Pioneering Screens Recording</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-efficiently-archive-your-content-vimeo-record-basics/"><u>2024 Approved Efficiently Archive Your Content Vimeo Record Basics</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/effective-strategies-when-atomic-hunter-gathers-limited-emails-using-massmail-software-solutions/"><u>Effective Strategies When Atomic Hunter Gathers Limited Emails: Using MassMail Software Solutions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-motorola-moto-g24-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Motorola Moto G24</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-spark-10-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Spark 10 5GFRP Lock</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/mastering-device-synergy-unifying-desktops-with-laptops-in-windows-11-real-world-examples/"><u>Mastering Device Synergy: Unifying Desktops with Laptops in Windows 11 - Real-World Examples</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-samsung-galaxy-xcover-6-pro-tactical-edition-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Samsung Galaxy XCover 6 Pro Tactical Edition.</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/mlining-shoots-with-smart-camera-tech-choices-for-2024/"><u>Streamlining Shoots with Smart Camera Tech Choices for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/swift-resolution-guide-for-horizontal-text-disruption-on-devices/"><u>Swift Resolution Guide for Horizontal Text Disruption on Devices</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/understanding-black-hat-seo-definitions-methods-and-potential-pitfalls/"><u>Understanding Black Hat SEO: Definitions, Methods, and Potential Pitfalls</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/understanding-dwell-time-in-seo-why-it-matters-and-how-to-boost-yours-expert-guide/"><u>Understanding Dwell Time in SEO: Why It Matters & How to Boost Yours | Expert Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-divide-superior-ai-versus-simpler-ai-techniques-explained/"><u>Understanding the Divide: Superior AI Versus Simpler AI Techniques Explained</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/unlocking-the-mystery-of-keywords-comprehensive-guide-and-proven-strategies-for-optimal-seo-performance/"><u>Unlocking the Mystery of Keywords: Comprehensive Guide and Proven Strategies for Optimal SEO Performance</u></a></li>
</ul></div>

