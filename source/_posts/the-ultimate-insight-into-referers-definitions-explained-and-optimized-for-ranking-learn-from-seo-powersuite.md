---
title: "The Ultimate Insight Into Referers: Definitions, Explained & Optimized for Ranking - Learn From SEO PowerSuite"
date: 2024-10-28T19:36:13.062Z
updated: 2024-10-31T22:54:08.849Z
tags:
  - wiki
categories:
  - link-assistant
thumbnail: https://thmb.techidaily.com/be26802ef5bb50783815300426404d3fea7e0b5a3f7f648e31ee7c5865304f02.jpg
---

## The Ultimate Insight Into Referers: Definitions, Explained & Optimized for Ranking - Learn From SEO PowerSuite

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Referer

### Contents

* [Definition](https://tools.techidaily.com/link-assistant/products/)
* [Functionality](https://tools.techidaily.com/link-assistant/products/)
* [Example](https://tools.techidaily.com/link-assistant/products/)
* [Preventing transmission of the referer information](https://tools.techidaily.com/link-assistant/products/)  
   * [Use a private browsing mode](https://tools.techidaily.com/link-assistant/products/)  
   * [Use a third-party privacy extension](https://tools.techidaily.com/link-assistant/products/)  
   * [Modify the browser settings](https://tools.techidaily.com/link-assistant/products/)  
   * [Use a different protocol](https://tools.techidaily.com/link-assistant/products/)
* [References](https://tools.techidaily.com/link-assistant/products/)

## Definition

In the context of the web, a referer (comes from the misspelled word _referrer_) is the URL of the previous webpage that linked to the current webpage[\[1\]](https://tools.techidaily.com/link-assistant/products/). It is used to identify where the user came from, and can be used to track user behavior and help websites understand how they are being accessed. The referer information is sent as a header field in an HTTP request, and can be used by the server to customize the content or behavior of the webpage based on where the user came from.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Functionality

In [HTML](https://tools.techidaily.com/link-assistant/products/), the referer information is not directly accessible to the webpage itself. Instead, it is passed as a header field in the HTTP request that is sent from the browser to the server when the webpage is requested. The server can then use this information to customize the content or behavior of the webpage in various ways.

One way to access the referer information on the server-side is to use the $\_SERVER\['HTTP\_REFERER'\] variable in PHP, or the request.headers.referer property in Node.js. On the client-side, you can use the Document.referrer property in JavaScript to access the referer information.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Example

Here is an example of how you might use the Document.referrer property in JavaScript to display a message on a webpage depending on where the user came from:

if (document.referrer.includes("google.com")) {

document.write("Welcome! You came from Google.");

} else if (document.referrer.includes("bing.com")) {

document.write("Welcome! You came from Bing.");

} else {

document.write("Welcome! We're not sure where you came from.");

Note that the Document.referrer property is not always reliable, as it can be blocked or modified by the browser or by third-party extensions. In addition, it is not available for security reasons when the user navigates to a webpage using a secure (HTTPS) connection from a page with an insecure (HTTP) connection.

## Preventing transmission of the referer information

There are a few ways that users can stop the transmission of the referer information:

### Use a private browsing mode

Many web browsers have a "private" or "incognito" mode that prevents the browser from storing history, search queries, and other data that could be used to track the user's activity. When private browsing mode is enabled, the browser will typically not send a referer header in HTTP requests.

### Use a third-party privacy extension

There are a number of browser extensions that can block or modify the referer header, as well as other headers and data that could be used to track the user's activity. Some examples of these extensions include Privacy Badger, Ghostery, and HTTPS Everywhere.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Modify the browser settings

In some cases, it may be possible to disable the referer header by modifying the browser settings. For example, in Mozilla Firefox, you can go to "Privacy & Security" in the Options menu, and then uncheck the "Send referrer header" option under the "Tracking Protection" section.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use a different protocol

If you need to access a webpage over a secure (HTTPS) connection, but the referer header is being blocked or modified, you can try using a different protocol, such as HTTP or FTP, to access the webpage. This will bypass the referer header entirely, but it may not be possible in all cases.

Keep in mind that while these methods can help to reduce the transmission of the referer information, they may not be completely effective in all cases, and they may have other trade-offs in terms of privacy and security.

## References

[1. https://en.wikipedia.org/wiki/HTTP\_referer](https://en.wikipedia.org/wiki/HTTP%5Freferer)

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
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-understanding-the-revenue-process-for-t-series-on-youtube/"><u>[Updated] In 2024, Understanding the Revenue Process for T-Series on YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-2023-sound-savvy-with-facebook-downloader/"><u>2024 Approved 2023 Sound Savvy with Facebook Downloader</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/boost-business-growth-dominate-the-market-by-luring-away-rivals-customers-with-stealth-marketing/"><u>Boost Business Growth: Dominate the Market by Luring Away Rivals' Customers with Stealth Marketing!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-30015-26-in-microsoft-365-for-desktops/"><u>Eliminating Error 30015-26 in Microsoft 365 for Desktops</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/essential-tips-for-creating-compelling-co-working-agreements-with-massmail-solutions/"><u>Essential Tips for Creating Compelling Co-Working Agreements with Massmail Solutions</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/how-to-perform-a-step-by-step-backup-of-your-data-on-windows-10-using-a-dell-computer/"><u>How to Perform a Step-by-Step Backup of Your Data on Windows 10 Using a Dell Computer</u></a></li>
<li><a href="https://win-able.techidaily.com/1723009336954-how-to-stop-diablo-iii-from-keep-collapsing-now-solved/"><u>How to Stop Diablo III From Keep Collapsing - Now Solved!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-y200-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo Y200 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/professionelle-tipps-fur-den-austausch-von-adressen-zwischen-ihrem-iphone-und-desktop-computer/"><u>Professionelle Tipps Für Den Austausch Von Adressen Zwischen Ihrem iPhone Und Desktop-Computer</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/seamless-migration-from-mbr-hdd-to-uefi-gpt-ssd-with-secure-boot-for-windows-11/"><u>Seamless Migration From MBR HDD to UEFI GPT SSD with Secure Boot for Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/updated-hp-printer-software-for-windows-11-easy-download-guide/"><u>Updated HP Printer Software for Windows 11: Easy Download Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/usb-audio-driver-updates-a-step-by-step-guide-for-windows-11107-users/"><u>USB Audio Driver Updates: A Step-by-Step Guide for Windows 11/10/7 Users</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/1728503940350-windows-11/"><u>Windows 11 復原失敗：如何解決初始化階段無法完成的問題？</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/year-in-review-the-best-of-figure-skating22/"><u>Year in Review The Best of Figure Skating'22</u></a></li>
</ul></div>

