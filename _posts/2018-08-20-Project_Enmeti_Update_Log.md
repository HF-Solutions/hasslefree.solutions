---
layout: post
title: Project Enmeti Update Log 2018/08/20
description: The first update regarding Project Enmeti, my vscode link inserting extension.
date: 2018-08-20
categories: VSCode JavaScript Extensions 100DaysOfCode
cover_image: https://i.imgur.com/K8Mn8lz.png
author_staff_member: Devin
---

# Project Enmeti Update Log #1

So, as I started my [100DaysOfCode][0] challenge, I [set out][1] to create an extension that would make it easier to insert links into Markdown files when writing articles, journal entries, whatever it is. I feel I have it at a comfortable state, however, I wanted to be able to try it out a bit more before I could say for sure.

For example, I'm writing this article not only to post an update that I've got this [extension working][2], but to test it out in a "production" environment 😅 As a result, the first thing I need to change is so that I can `Alt+Tab` away from VSCode to actually _get_ the link I need, and the input box not disappear...

Ahhh, [there we go][3] 🤗 Much better. 

Up next, what if you try to add a link that's already been added? Why add it twice when we can just reference the [pre-existing link?][6]

## How to Use It

So instead of just talking about the extension, how about I show you how to use it? The simplest way to insert a link would be to select some text, right click, and then select `Insert Link`. It will show an **InputBox** so you can give it the URL of your link:

![Example-1][10]

As you can see in the gif, you can also use the default `Ctrl+Alt+I` keybinding, or even change it to whatever you prefer in [keybindings.json][7]:

![Keybindings.json][11]

## Up Next

Thanks to [a great suggestion][8] by [Andrew Bone][9], my next step is to make it so you can insert images similarly to how links are inserted. What I'm thinking is something along the lines of:

- Select the text to turn into an image
- Execute the command (`Ctrl+Shift+I`)
- Input the path to the image in an **InputBox**
- Add the reference to the image at the end just as we do links

As usual, any and all input is welcome and much appreciated 😊

[0]: https://www.100daysofcode.com
[1]: https://dev.to/hf-solutions/project-enmeti-o0g
[2]: https://marketplace.visualstudio.com/items?itemName=hf-solutions-llc.enmeti
[3]: https://github.com/HF-Solutions/Enmeti/commit/66eb63d3951329eb704f4ca03b64eb3e96cdd4b4
[4]: https://unsplash.com
[5]: https://unsplash.com/photos/BnWDqUCWQDU?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText
[6]: https://github.com/HF-Solutions/Enmeti/commit/c1d5c504a854036eea134464a21e1bcf8ae4af5a
[7]: https://code.visualstudio.com/docs/getstarted/keybindings
[8]: https://dev.to/link2twenty/comment/4k81
[9]: https://dev.to/link2twenty
[10]: https://thepracticaldev.s3.amazonaws.com/i/zesvk29zyzdqlgvlvqp8.gif
[11]: https://i.imgur.com/7NKAy7e.png