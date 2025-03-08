---
title: "Introducing the Latest Karaoke Kit: Enhanced Playback with SongLibrary DB Integration Now Available for Testing"
date: 2025-03-06T20:11:58.729Z
updated: 2025-03-07T16:35:08.094Z
tags:
  - product
categories:
  - pcdj
thumbnail: https://thmb.techidaily.com/c38adae2e42bb33172470753ec027ccdb4d1aafb812ed418ac2e91f37424af9f.jpg
---

## Introducing the Latest Karaoke Kit: Enhanced Playback with SongLibrary DB Integration Now Available for Testing

[![](https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?resize=530%2C298&ssl=1)](https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?fit=530%2C298&ssl=1 "karaokibeta-songbookdbcover")

It’s [karaoke software](https://tools.techidaily.com/pcdj/products/) beta test time, now with direct in-application integration of SongbookDB’s internet based remote request plugin.

Last week we posted about [how the SongbookDB integration in Karaoki will work](https://tools.techidaily.com/pcdj/products/), now we call on KJs to download and try the new beta now. Included in this beta are multiple performance upgrades and other new features to try.

#### Here are all the details and info below on how you can download and test the latest beta today:

**Karaoki Beta 0.8.5419** Notes:

_You will notice that there is a new item on the ‘Options’ button menu ‘Remote Connections’ and when clicked you will see a new screen. This screen is similar to the old ‘Remote Request Station’ area that was on the config screen and if you have used the old interface shouldn’t have any issues using the new screen._

[![](https://i1.wp.com/pcdj.com/wp-content/uploads/2014/10/Songbook-Plugin.png?fit=300%2C183&ssl=1 "Songbook Plugin")](https://i1.wp.com/pcdj.com/wp-content/uploads/2014/10/Songbook-Plugin.png?fit=981%2C601&ssl=1)

The majority of the new screen (the entire lower half and the ‘Cases’ drop down list) is for the existing ‘Remote Terminal’ application and for similar future plugins, this lower section is not used for the SongbookDB plugin as it manages its own incoming requests itself.

**Here are a few pointers.**  
Most of the items on the upper section of the screen should already be familiar to you and so I’ll only go over any changes…

**Changing the port:**  
Karaoki will probably have the port set to 6000 as this is the old default, however, the new plugin will have its port set to 81 by default so it will have to be changed either in Karaoki or on the plugin.. In Karaoki the port can only be changed when the ‘Remote’ is disabled using the ‘Enable/Disable’ button (the large top left button on the new screen). So to change the port, If enabled, disable the remote connections using the ‘Enable/Disable’ button, Change the port number in the port box, then re-enable the remote connections using the Enable button.

**Remote Options:**  
1.) ‘Shutdown Client Applications/Plugins on Exit’: when checked Karaoki will send the ‘shutdown’ command to any connected plugin before it closes, If the plugin supports this command the plugin should then close.  
2.) ‘Disable Request Alerts’: when Karaoki receives a singers request it will notify you by flashing a message on the main screen and on the ‘Remote Connections’ screen, Checking the option disables the flashing massages as they could be annoying to some users.

_**The lower half of the screen… ‘Remote Request Station’ (and any future equivalents) only:**_

Requested Tracks list: when Karaoki receives a track form ‘Remote Request station’ the request is now placed in this list where it will remain until it is ‘Accepted’ or Declined’, Accepting the request will transfer the request to Karaoki’s rotation, ‘Declining’ the request will remove the request from the list.

**Ban:** If you have a singer that’s being a PITA you now have the option to ‘Ban’ Him/Her, when banned any requests from the banned individual are ignored and will not be added to the ‘Requested Tracks’ list.

**‘Auto Accept’ option:** when checked all incoming requests are automatically accepted, so when receiving incoming requests from a ‘Remote Request Station’ Karaoki will behave as it did in previous builds and place the requested tracks directly into rotation.

[![](https://i2.wp.com/pcdj.com/wp-content/uploads/2014/10/Karaoki-Remote-Users..png?fit=300%2C188&ssl=1 "Karaoki Remote Users.")](https://i2.wp.com/pcdj.com/wp-content/uploads/2014/10/Karaoki-Remote-Users..png?fit=594%2C374&ssl=1)

**General use:**  
When a request is sent from a terminal or via SongbookDB an alert message will flash on Karaoki’s main screen and also in the ‘Remote Connections’ screen, clicking on the message on the main screen will cancel the message and display either the SongbookDB plugin (for requests from SongbookDB users) or the ‘Remote Connections’ screen (for all other requests), the request will then need to be ‘Accepted’ (‘add +’ on the SongbookDB plugin) for it to be added to the rotation.

**_That’s it!!_**

**Here’s a list of all Fixes, Additions and Changes since the last beta.**

_**Build #0.8.5419.37065 Nov 2nd 2014**_  
Added: SongbookDB plugin integration and ‘Remote Connections’ screen added.  
Added: ‘/lockcases’ command line switch and ‘Ctrl+Shift+W’ Key Combo that hides the ‘Min’, ‘Max’, ‘Exit’, ‘Options’, ‘Add Case’ and ‘Add Songs’ buttons.  
Change: Remote Terminal interface enhanced and moved to ‘Remote Connections’ screen.  
Change: New Licencing System.  
Change: A Few skin changes.  
Fixed: Karaoki not reading some ID3 tags correctly.  
Fixed: Karaoki not displaying ‘&’ on singer screen and preview display and ticker.  
Fixed: Karaoki cutting ticker message short if it contains a carriage return, the Ticker is now limited to 250 characters.  
Fixed: Preview player not working on Win 8 onwards.

[Download Karaoki Beta With SongbookDB Integration](https://tools.techidaily.com/pcdj/products/)

[SongBookDB Video Tutorials - See How It Works!](https://www.songbookdb.com/docs/djs/tutorialVideos/)

ALL BETA REPORTS FOR KARAOKI CAN BE POSTED [HERE ON THE PCDJ FORUM](https://tools.techidaily.com/pcdj/products/)

#### To Gain Access To The SongbookDB Custom PCDJ Plug-In, Fill Out The Form Below. We Will Get Back To You Shortly With Testing Details

### _Related_

https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?fit=530%2C298&ssl=1 298 530 Ryan Sherr https://www.pcdj.com/wp-content/uploads/2021/07/pcdj-main-logo-2.png Ryan Sherr2014-11-04 09:59:272023-04-10 17:04:33Karaoki Beta Test Launched with SongBookDB Integration}

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-filmmaking-simplified-create-an-inviting-youtube-subscription-button-in-filmora/"><u>[New] 2024 Approved Filmmaking Simplified Create an Inviting YouTube Subscription Button in Filmora</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-timing-translation-from-20mb-to-seconds-measurement/"><u>[New] 2024 Approved Timing Translation From 20Mb to Seconds Measurement</u></a></li>
<li><a href="https://article-files.techidaily.com/new-key-tips-for-attracting-brands-as-youtubers-sponsors/"><u>[New] Key Tips for Attracting Brands as Youtubers' Sponsors</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-the-finest-4k-displays-for-precise-color-control/"><u>[New] The Finest 4K Displays for Precise Color Control</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-discover-the-top-5-pc-clipping-utilities-for-quick-samples/"><u>[Updated] 2024 Approved Discover the Top 5 PC Clipping Utilities for Quick Samples</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/ver-winx-dvd-ripper-dvd/"><u>最新Ver.] WinX DVD Ripper - プロ用DVDリッピングツールを強力に！</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/beginners-guide-to-creating-your-first-successful-youtube-video-key-strategies-and-advice/"><u>Beginner's Guide to Creating Your First Successful YouTube Video: Key Strategies & Advice</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/deverrouiller-et-convertir-des-filmsemissions-disneys-en-dvd/"><u>Déverrouiller Et Convertir Des Films/Émissions Disneys en DVD</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/guide-ultime-utiliser-winx-video-pour-une-qualite-professionnelle-lors-du-recueil-decrans-webcam-et-audio/"><u>Guide Ultime: Utiliser WinX Video Pour Une Qualité Professionnelle Lors Du Recueil D'écrans Webcam Et Audio</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-unveiling-the-art-of-documenting-real-time-facetime-discussions/"><u>In 2024, Unveiling the Art of Documenting Real-Time FaceTime Discussions</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/isowindows-11-windows-11iso-5/"><u>ISOファイルをWindows 11で使い始めるための無料ソフトランキング - Windows 11ISO オススメソフト5選</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/the-top-10-no-cost-4k-media-players-supporting-windows-11-and-mac-computers/"><u>The Top 10 No-Cost 4K Media Players Supporting Windows 11 & Mac Computers</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/ultimate-guide-top-10-premier-anime-streaming-websites-with-recent-updates/"><u>Ultimate Guide: Top 10 Premier Anime Streaming Websites with Recent Updates</u></a></li>
</ul></div>

