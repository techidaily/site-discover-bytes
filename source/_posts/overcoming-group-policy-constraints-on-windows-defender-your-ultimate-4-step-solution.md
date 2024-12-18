---
title: Overcoming Group Policy Constraints on Windows Defender – Your Ultimate 4-Step Solution
date: 2024-12-11T20:42:55.162Z
updated: 2024-12-18T04:21:11.432Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why “Windows Defender blocked by Group Policy” Error Occurs?

There could be a number of reasons for this error to happen. Here are the most common ones.

* Another [third-party antivirus](https://tools.techidaily.com/malwarefox/products/) or antimalware is clashing with the Windows Defender program.
* Cybercriminals might have used infiltrate Group Policy using [malware](https://tools.techidaily.com/malwarefox/products/) to disable the security of the Windows system.
* Some unauthorized changes in the Group Policies can also lead to the error. The changes can be made by mistake or intentionally too.

## How to fix “Windows Defender is Turned off by Group Policy”?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Using Group Policy Editor**

**_Note_**_: The Group Policy Editor is not available on the Windows 10 Home version_

1. Search for the **Group Policy Editor** in the windows search bar and launch it.![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. In the editor, navigate to: **Computer Configuration** \-> **Administrative Templates** \-> **Windows Components** \-> **Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Locate “**Turn off Microsoft Defender Antivirus**” and double click on it to open it.![Turn Off Microsoft Defender Antivirus](https://www.malwarefox.com/wp-content/uploads/2020/10/Turn-Off-Microsoft-Defender-Antivirus.png)
4. In order to enable the Microsoft Defender, click on the **Disabled** bullet.![Enable-MS-Defender](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-Defender.png)

5. Click **Apply** and **OK** to finish the configuration.

6. Restart the system to enable the settings.

---

### **Using Registry Editor**

1. Search for “**Registry Editor**” in the windows search box and launch it.![launch registry editor](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-registry-editor.png)
2. Navigate to or copy & paste this path to reach the Windows Defender folder: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender**

3. Right-click on the **DisableRealTimeMonitoring** key and Delete it.![Delete DisableRealtimeMonitoring key](https://www.malwarefox.com/wp-content/uploads/2020/10/Delete-DisableRealtimeMonitoring-key.png)
4. Exit from the Registry Editor and reboot your system to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Using the PowerShell Command**

1. Search for the **Windows Powershell** in the Windows search box and select **Run as Administrator.**![PowerShell Run as Admin](https://www.malwarefox.com/wp-content/uploads/2020/10/PowerShell-Run-as-Admin.jpg)
2. Type or copy & paste this command and hit the enter key: **_Set-MpPreference -DisableRealtimeMonitoring 0_**![Enable MS defender with Powershell](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-defender-with-Powershell.png)

---

### **Using Windows Settings**

1. Right-click on the windows start icon and choose Settings from the list.![Settings](https://www.malwarefox.com/wp-content/uploads/2020/10/Settings.png)
2. Select **Update & Security** settings.![Update and Security](https://www.malwarefox.com/wp-content/uploads/2020/10/Update-and-Security.png)
3. From the left-pane choose **Windows Security**![launch windows security](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-windows-security.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, click on **Virus & threat protection**.![Choose virus & threat protection](https://www.malwarefox.com/wp-content/uploads/2020/10/Choose-virus-threat-protection.png)
5. Navigate to Virus & threat protection settings and click on **Manage settings**.![manage V&T settings](https://www.malwarefox.com/wp-content/uploads/2020/10/manage-VT-settings.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Toggle the switch to turn on the Microsoft Defender **real-time protection**.![turn On the Real Time protection](https://www.malwarefox.com/wp-content/uploads/2020/10/turn-On-the-RT-protection.png)

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
<li><a href="https://fox-boxes.techidaily.com/2024-approved-cut-to-quality-perfecting-videos-with-enhancer-22/"><u>2024 Approved Cut to Quality Perfecting Videos with Enhancer 2.2</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mac-mavericks-blueprint-for-crafting-captivating-youtube-content/"><u>2024 Approved Mac Mavericks' Blueprint for Crafting Captivating YouTube Content</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-tecno-spark-go-2023-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Tecno Spark Go (2023) Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-modern-wallet-navigating-iphone-and-apple-watch-for-effortless-apple-pay-usage/"><u>The Modern Wallet: Navigating iPhone and Apple Watch for Effortless Apple Pay Usage</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/top-5-seo-tools-for-boosting-your-b2b-niche-visibility/"><u>Top 5 SEO Tools for Boosting Your B2B Niche Visibility</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/troubleshooting-guide-locating-the-reset-this-pc-feature-on-windows-10/"><u>Troubleshooting Guide: Locating the 'Reset This PC' Feature on Windows 10</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/under-45-over-cooling-performance-the-ultimate-deal-with-the-deepcool-as500-plus-air-cooler-on-amazon/"><u>Under $45, Over Cooling Performance: The Ultimate Deal with the DeepCool AS500 Plus Air Cooler on Amazon</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/issledovanie-pervoklassnyh-agentstv-po-seo-v-omane-effektivnoe-poyavlenie-interneta-s-ispolzovaniem-seo-powersuite/"><u>Исследование Первоклассных Агентств По SEO В Омане - Эффективное Появление Интернета С Использованием SEO-PowerSuite</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/najdite-luchshie-instrumenty-dlya-seo-i-reklamy-usovershenstvovat-onlajn-prisutstvie-vashego-predpriyatiya-s-opytnymi-agentstvami-iz-rima-italiya/"><u>Найдите Лучшие Инструменты Для SEO И Рекламы: Усовершенствовать Онлайн-Присутствие Вашего Предприятия С Опытными Агентствами Из Рима, Италия!</u></a></li>
</ul></div>

