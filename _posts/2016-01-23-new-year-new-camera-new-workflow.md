---
title: New Year, New Camera, New Workflow
author: tiernano
layout: post
categories:
  - Workflow
  - Camera Gear
---
Happy New Year! Its been a while, but hopefully this is the first of many new posts... To start, this post is a quick overvew of my new (planned, but not fully "production" tested) workflow. And the reason for it... 

As the title says, there is a new camera i am using. I pulled the trigger and bought a [Canon 5DS][1] after selling my [6D][2]. Its a pretty impressive peice of kit. 50MP resolution, with the option of shooting cropped at 1.3 or 1.6. When shooting cropped, the images are about 30ish MP at 1.3 and 20ish at 1.6. but it does, techincally, increese the zoom... so, shooing on a 100mm lense, at 1.3 its 130, and at 1.6 its 160... havent used that yet... i usually crop during post. Image size wise, the JPGs are weighting in at about  15-17MB each and the RAW images are in around high 60s low 70MB range... 

![image file sizes][10]

Which meant upgrading all my cards to larger ones and also upgrading the readers. It shoots of both CF and SD, so i shoot with a couple of [Lexar Professional 800x 64Gb CF][3] and a few [Sandisk Extreme 64Gb SDXC] cards, aswell as an [EyeFi Mobi Pro 32Gb][5] every now and again... Reading wise, its Lexar again, using the [Lexar Professional Workflow system] with a HR1 hub (which, due to a techincal issue with the wrong power supply, i may have let the magical blue smoke out of and need to replace...) a 512Gb data drive, 2 CF and 2 SD readers. other than blowing up the hub (and possibly one of the CF readers... i was jetlagged and very sleepy) the rest is going very well! 

So, now on to the workflow explaination! So, i take photos, shooting RAW to the CF and JPGs to the SD. I get home (but could be anywhere) and i download the photos to a given folder. I use [Lightroom][7], and depending on the shoot, may create a new catalog or use an existing one. Either way, the photos are stored in a particular folder, as are the lightroom catalogs. I make my changes, and thats it... Normal enough workflow, right? Well, the folder location is kind of important. I use [BitTorrent Sync][8] for syncing folders around the place. My main workstation, my Mac Mini and my laptop all sync both the catalog and photos folder. In the case of the laptop, it is using selective sync. When new files are dropped into these folders, or change, they are synced with any other machine with that folder. So, photos downloaded on the laptop are synced with the Mac Mini and GodBox2, assuming its got an internet connection. same with changes to the catalogs. 

Again, this is not fully battle tested, just yet. I am still tweaking this, but so far, so good... And as an added bonus, [BTSync 2.3][9], which launched a few days ago, included a feature called Encrypted Folders. Essentially, you create one of these on your workstations, and it gives you 3 sharing keys: One is Read/Write, for normal use, one of Read only, so for clients checking files, say, and a third is Encrypted. so, for example, if you have a Dedicated server or a Cloud server somewhere, and want to use it for bandwidth, but dont want to have your files sitting there, unprotected, they are now stored on that server encrypted. Laptops and workstations can still use work with this machine, syncing data and can still make changes to it, but it will always be encrypted on their end. Very cool stuff! 


[1]: http://www.geekphotographer.com/canon-announce-5ds-and-5ds-r-with-50mp-sensors-and-some-other-stuff/
[2]: http://www.geekphotographer.com/canon-announce-eos-6d-dslr-and-3-new-powershots/
[3]: http://www.amazon.co.uk/gp/product/B00HYRF8H2/ref=as_li_tl?ie=UTF8&camp=1634&creative=19450&creativeASIN=B00HYRF8H2&linkCode=as2&tag=tiescomclo-21
[4]: http://www.amazon.co.uk/gp/product/B013CP3MMM/ref=as_li_tl?ie=UTF8&camp=1634&creative=19450&creativeASIN=B013CP3MMM&linkCode=as2&tag=tiescomclo-21
[5]: http://www.amazon.co.uk/gp/product/B00UADC43I/ref=as_li_tl?ie=UTF8&camp=1634&creative=19450&creativeASIN=B00UADC43I&linkCode=as2&tag=tiescomclo-21
[6]: http://www.amazon.co.uk/s/ref=as_li_ss_tl?_encoding=UTF8&camp=1634&creative=19450&field-keywords=lexar%20professional%20workflow&linkCode=ur2&rh=i%3Aaps%2Ck%3Alexar%20professional%20workflow&tag=tiescomclo-21&url=search-alias%3Daps
[7]: http://bit.ly/1cHsDqi
[8]: https://www.getsync.com/
[9]: https://blog.getsync.com/2016/01/21/sync-2-3-brings-more-features-for-power-users/
[10]: /wp-content/uploads/2016/01/20160123-filesize.PNG
