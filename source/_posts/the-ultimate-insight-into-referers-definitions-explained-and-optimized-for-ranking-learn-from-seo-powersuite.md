---
title: "The Ultimate Insight Into Referers: Definitions, Explained & Optimized for Ranking - Learn From SEO PowerSuite"
date: 2024-10-15T17:02:15.800Z
updated: 2024-10-19T22:38:23.825Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Functionality

In [HTML](https://tools.techidaily.com/link-assistant/products/), the referer information is not directly accessible to the webpage itself. Instead, it is passed as a header field in the HTTP request that is sent from the browser to the server when the webpage is requested. The server can then use this information to customize the content or behavior of the webpage in various ways.

One way to access the referer information on the server-side is to use the $\_SERVER\['HTTP\_REFERER'\] variable in PHP, or the request.headers.referer property in Node.js. On the client-side, you can use the Document.referrer property in JavaScript to access the referer information.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use a private browsing mode

Many web browsers have a "private" or "incognito" mode that prevents the browser from storing history, search queries, and other data that could be used to track the user's activity. When private browsing mode is enabled, the browser will typically not send a referer header in HTTP requests.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047366/19272" target="_top" id="2047366">
  <img src="//a.impactradius-go.com/display-ad/19272-2047366" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use a third-party privacy extension

There are a number of browser extensions that can block or modify the referer header, as well as other headers and data that could be used to track the user's activity. Some examples of these extensions include Privacy Badger, Ghostery, and HTTPS Everywhere.

### Modify the browser settings

In some cases, it may be possible to disable the referer header by modifying the browser settings. For example, in Mozilla Firefox, you can go to "Privacy & Security" in the Options menu, and then uncheck the "Send referrer header" option under the "Tracking Protection" section.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-guidance.techidaily.com/new-pricing-outline-the-cost-to-film-melodies-visually/"><u>[New] Pricing Outline The Cost to Film Melodies Visually</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-tutorial-extracting-audio-from-vimeo-video-for-2024/"><u>[New] Tutorial Extracting Audio From Vimeo Video for 2024</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/gli-strumenti-piu-efficienti-per-la-pulizia-ed-il-restauro-degli-ssd-adata-guida-definitiva/"><u>Gli Strumenti Più Efficienti per La Pulizia Ed Il Restauro Degli SSD AData: Guida Definitiva</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-oppo-k11-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Oppo K11 5Gwith/without a PC</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-6s-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 6s without iTunes? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/introducing-enhanced-graphics-driver-for-win10s-nvidia-210/"><u>Introducing Enhanced Graphics Driver for Win10's NVIDIA 210</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/leading-non-integrated-photo-editors-optimized-for-windows-users/"><u>Leading Non-Integrated Photo Editors Optimized for Windows Users</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/macrium-reflect-free/"><u>Macrium Reflect Freeの自由ダウンロードと優れたバックアップツールの選び方:実践的チュートリアル</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/missing-content-alert-404-not-located/"><u>Missing Content Alert: 404 Not Located</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-high-refresh-monitor-selection/"><u>Optimal High Refresh Monitor Selection</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/solution-melatonin-helps-regulate-the-bodys-internal-clock-signaling-when-it-is-time-to-sleep-disruptions-in-its-production-can-lead-to-circadian-rhythm-dis53/"><u>Solution: Melatonin Helps Regulate the Body's Internal Clock, Signaling when It Is Time to Sleep. Disruptions in Its Production Can Lead to Circadian Rhythm Disorders Like Insomnia or Delayed Sleep Phase Syndrome.</u></a></li>
<li><a href="https://win-dash.techidaily.com/solving-hp-beats-speaker-drivers-issues-on-your-pc-running-windows-11-8-or-7-step-by-step-fixes/"><u>Solving HP Beats Speaker Drivers Issues on Your PC Running Windows 11, 8 or 7 - Step-by-Step Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-itel-p55plus-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Itel P55+? Here is How | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726026778344-youtube/"><u>YouTube動画の複数回再生方法を理解する:手っ取り早いガイド</u></a></li>
</ul></div>

