---
published: true
title: Raspberry Pi NAS - Nope
layout: post
---
I've had a bit of a play with the different Raspberry Pi computers for awhile now.  Got myself the latest 3rd edition one in hope I could setup a NAS.  Don't use a Raspberry Pi for a NAS, why - it only has 100mb ethernet.  I have plugged in a few external drives and the best transfer speed I can get is around 5mb/s.  Plugged into a USB port it would be around 25mb/s. So you are looking at quite a slowdown from a USB2 drive.

What alternative is there?  Well I have a ODROID-XU4 in the post, about twice the cost with the eMMC memory card and case as the Raspberry Pi.  The XU4 does have gigabit ethernet, and using the eMMC it should boot up quite fast, the processor is faster also.  The drawback is it only has two USB ports, so I will have to purchase a hub to use more drives.  It doesn't have wifi also, but don't need this for the NAS as using ethernet.

Software?  Well I think there's only one easy option that works great and it's Openmediavault.  If you want to run FreeNAS with ZFS then you're looking at needing around 8gig of RAM.  Openmediavault is based on Debian and does everything you need - especially love being about to leave the torrents running quietly 24 hours a day.
