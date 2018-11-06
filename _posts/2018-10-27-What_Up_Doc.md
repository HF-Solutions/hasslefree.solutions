---
layout: post
title: What's Up Doc?
description: An update on things I've been doing since my last blog post and what I've got planned.
categories: update life news projects
tags: update, life, news, projects
cover_image: https://i.imgur.com/JdGz1Fh.png
author_staff_member: Devin
date: 2018-10-27
published: true
---

_Cover photo by [rawpixel][19] on [Unsplash][20]_

Well, it's certainly been too long since my last blog post, so this is a catch-all for the things I've done since I last published and what my plans are now that the holiday season is approaching.

## Tron

Of course, I've been working on my baby, [Tron][0] by fixing bugs and adding a command that had been requested for some time.

- Bug Fixes:
  - [Fixed the `+adopt` command][5] to works as expected instead of not replying.
  - [Added Try/Catches][4] to help prevent **PermissionsDenied** errors that were crashing Tron.
  - [Fixed the `+reddit` command][3] so it properly displays an image from the requested subreddit.
  - [Fixed the `+birthday` command][1] so it properly saves birthdays.
    - For some reason I forgot to pass the client so it wasn't actually saving anything.
  - [Fixed the `+marriage` command][2] so it would accept input from the correct user.
  - [Fixed the `getImage()` function][7] so it would check the values properly.
  - [Fixed the `onCommandRun` event][8] so it wouldn't crash if the user tried running a command in DM's.
- Added:
  - [Added the Purge command][6] as requested by a few users.

## Enmeti

I managed to get [Enmeti][9] to a respectable state and it is now at version 1.1.1. You can insert links and/or images in place of existing text, on a blank line or in place of your cursor. I still have some more work to do, specifically with detecting the bottom of the file, but I believe it's in a much better place than when [I previously wrote about it][10].

For more information, check out the extension on the [Visual Studio Code Marketplace][9], or visit the [repository on GitHub][11] 😊

## Personal/Company Website

For the longest time, [my company website][13] was hosted on [SquareSpace][12] until recently when I discovered the joy of [GitHub Pages][14]. After tinkering with it for a week or two, I managed to get comfortable enough that I created what is now [my new website][13] for **HassleFree Solutions, LLC**. When I completed the **HassleFree Solutions** site, I was confident that I could get [my own personal site][15] setup using a different theme and with blogging support. I'm using the [Material-Jekyll-Theme][16] created by [Alex Carpenter][16] for my personal site, while my company website uses the [Time Machine theme][17] with a bit of customization done by myself to make it look a bit nicer (imo).

## Conclusion

I need to write more! While I feel like I've done a lot of stuff since I last wrote, I don't feel quite as accomplished as I do when I also write about what I've been working on. So, with that said I intend to write something at least once a week and publish it whether or not I'm happy about it 😅

That said, if you have any comments, criticisms, or suggestions, please don't hesitate to let me know! There's a number of ways to contact me on my [personal site][18].

[0]: https://github.com/HF-Solutions/Tron
[1]: https://github.com/HF-Solutions/Tron/commit/2837581548dd7829e031e24179b8542843be66f8
[2]: https://github.com/HF-Solutions/Tron/commit/35c7b8340e30226845e97035596cd2f7001fd0c9
[3]: https://github.com/HF-Solutions/Tron/commit/0a430de6a4aacb4d3f58d2305e6bee0c02f0d6d0
[4]: https://github.com/HF-Solutions/Tron/commit/96163b2716b76e01ff56e65cf923b6aeb8b1d9ce
[5]: https://github.com/HF-Solutions/Tron/commit/78c7298b6a3475fb85c170fc09ca03721564c43f
[6]: https://github.com/HF-Solutions/Tron/commit/7a67b9681a4b26d23b35e69a846d724c368ffa31
[7]: https://github.com/HF-Solutions/Tron/commit/bade884f7954a08262374aef3cc92daa03ecb94a
[8]: https://github.com/HF-Solutions/Tron/commit/bf4745311e233aabde5ce2249cb361445dfed9f7
[9]: https://marketplace.visualstudio.com/items?itemName=hf-solutions-llc.enmeti
[10]: https://dev.to/hf-solutions/project-enmeti-update-log-20180820-4297
[11]: https://github.com/HF-Solutions/Enmeti
[12]: https://www.squarespace.com/
[13]: https://hasslefree.solutions
[14]: https://pages.github.com
[15]: https://alcha.org
[16]: https://github.com/alexcarpenter/material-jekyll-theme
[17]: https://pages-themes.github.io/time-machine/
[18]: https://alcha.org/#contact-info
[19]: https://unsplash.com/photos/mGVhGkvBTYc
[20]: https://unsplash.com/search/photos/update
[21]: https://i.imgur.com/JdGz1Fh.png