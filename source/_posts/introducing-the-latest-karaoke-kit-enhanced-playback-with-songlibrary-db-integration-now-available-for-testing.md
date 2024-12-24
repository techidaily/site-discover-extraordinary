---
title: "Introducing the Latest Karaoke Kit: Enhanced Playback with SongLibrary DB Integration Now Available for Testing"
date: 2024-12-17T04:29:04.776Z
updated: 2024-12-23T19:59:25.893Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-perfecting-screen-capture-teams-meetings-on-pctablet/"><u>[New] 2024 Approved Perfecting Screen Capture Teams' Meetings on PC/Tablet</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mastering-youtube-earnings-a-comprehensive-viewer-count-analysis-for-2024/"><u>[Updated] Mastering YouTube Earnings A Comprehensive Viewer Count Analysis for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-igniting-online-frenzy-essential-trending-hashes/"><u>2024 Approved Igniting Online Frenzy Essential Trending Hashes</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/accelerating-your-computer-effective-tips-from-yl-computings-expert-guide/"><u>Accelerating Your Computer: Effective Tips From YL Computing's Expert Guide</u></a></li>
<li><a href="https://discover-data.techidaily.com/building-your-crypto-asset-collection-a-step-by-step-guide-by-yl-computing/"><u>Building Your Crypto Asset Collection: A Step-by-Step Guide by YL Computing</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/high-quality-hd-wallpaper-collection-the-iconic-bentley-bentayga-speed-edition-enhance-your-screen-with-premium-visuals-from-yl-computing/"><u>High-Quality HD Wallpaper Collection: The Iconic Bentley Bentayga Speed Edition - Enhance Your Screen with Premium Visuals From YL Computing</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/pioneer-dj-controlers-setup-guide-mastering-general-configuration-options/"><u>Pioneer DJ Controlers Setup Guide: Mastering General Configuration Options</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/premium-dodge-hornet-visuals-for-pc-screensavers-and-banners-curated-collection-from-yl-computing/"><u>Premium Dodge Hornet Visuals for PC Screensavers and Banners - Curated Collection From YL Computing</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/safe-methods-to-restore-permanently-deleted-images-from-your-iphone/"><u>Safe Methods to Restore Permanently Deleted Images From Your iPhone</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/seamlessly-add-dynamic-flipbooks-to-your-sites-homepage-via-flipbuilder-tutorial/"><u>Seamlessly Add Dynamic Flipbooks to Your Site's Homepage via FlipBuilder Tutorial</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/showdown-how-does-the-apple-tv-4k-stack-up-against-the-roku-ultra/"><u>Showdown: How Does the Apple TV 4K Stack Up Against the Roku Ultra?</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/solving-wi-fi-connectivity-problems-on-windows-11-a-step-by-step-guide-expert-tips-from-yl-computing/"><u>Solving Wi-Fi Connectivity Problems on Windows 11: A Step-by-Step Guide - Expert Tips From YL Computing</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/subscribe-for-endless-music-parties-discover-fresh-tracks-from-new-party-tymes-2018-karaoke-set/"><u>Subscribe for Endless Music Parties! Discover Fresh Tracks From New Party Tyme's 2018 Karaoke Set</u></a></li>
<li><a href="https://fox-that.techidaily.com/understanding-the-limitations-5-barriers-to-gift-sending-on-iphones-and-ipads/"><u>Understanding the Limitations: 5 Barriers to Gift-Sending on iPhones and iPads</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/yl-computing-expert-advice-how-to-quickly-and-safely-uninstall-software-you-dont-need-anymore/"><u>YL Computing Expert Advice: How to Quickly and Safely Uninstall Software You Don't Need Anymore</u></a></li>
</ul></div>

