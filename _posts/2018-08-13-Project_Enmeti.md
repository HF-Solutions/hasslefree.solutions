---
layout: post
title: Project Enmeti
description: A simple extension for Visual Studio Code to help insert links.
date: 2018-08-13
categories: vscode extension JavaScript 100DaysOfCode
cover_image: https://i.imgur.com/ldKDy7A.png
author_staff_member: Devin
---

## My First Real VSCode Extension

In [my post][0] where I talk about starting the #100DaysOfCode challenge, I mentioned one of the potential things I'd work on would be an extension for Visual Studio Code that would help me with inserting links into my Markdown files. This is particularly useful when writing posts such as this one where I do all the writing in a Markdown file on my machine and then copy/paste the content to [dev.to][1] or any other site I'm posting it to.

This is something I found particularly annoying to do, considering how simple and repetitive the process is:

1. Select the text to turn into a link.
2. Add the `[` brackets around it.
3. Add a [x + 1] reference where x is number of the _last_ link I added to the post.
4. Add the reference to the bottom of the file with the link next to it.

While not overly difficult, if you've ever automated/simplified a mundane task then you know the feeling I'm talking about.

## Enter Enmeti

Which leads me to today, where I've actually posted the code online in a [GitHub repo][2]. So far, the extension has nothing more than an `extension.insertLink` command that will surround your selected text with brackets and add a `[0]` reference to the end of it. Nothing fancy to say the least 😅 However, it's a good start as far as I can tell, since I've got the basis for making edits to the currently selected text, and I had _no_ idea how to do that when starting this.

So far, the work I've managed to complete was largely thanks to the [yo generator][3] for Visual Studio Code extensions, the [MDTools example][4], and the [VSCode API documentation][5]. So, a massive thank you to those who took part in those projects.

That's all I've got for today, and I'll be sure to post more updates as I get further along 😊

[0]: https://dev.to/hf-solutions/100-days-of-code-challenge-3j5h
[1]: https://dev.to
[2]: https://github.com/HF-Solutions/Enmeti
[3]: https://code.visualstudio.com/docs/extensions/yocode
[4]: https://github.com/Microsoft/vscode-MDTools
[5]: https://code.visualstudio.com/docs/extensionAPI/overview
[6]: https://unsplash.com/@dcanies
[7]: https://unsplash.com