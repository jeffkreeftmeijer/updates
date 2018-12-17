---
date: 2018-12-17T08:27:01Z
in_reply_to: https://www.reddit.com/r/vim/comments/a1irnz/consistent_terminal_colors_with_16ansicolor_vim/ebtn99c/
reddit: https://www.reddit.com/r/vim/comments/a1irnz/consistent_terminal_colors_with_16ansicolor_vim/ebyuifz/
---

Great to hear you’re using Dim!

Those automatically-changing background colors are a great find, indeed. I'm currently using ⌘+I to switch between my dark and light themes in Terminal.app, but changing the system-wide appearance and having the background update automatically would be nice to support for custom themes. 

Dim’s syntax highlighting is consistent on dark and light backgrounds, but the gray colors can be tweaked by changing the `bg` value. (`:set bg=dark` on dark backgrounds, `:set bg=light` on light ones). That will dim the gray line numbers and color columns to use “white” (7) on light themes or “bright black” (8) on dark ones.

I haven’t found a way to automate that yet, because you can’t seem to read the background color value from the current theme. But since we can check the appearance in macOS (`defaults read -g AppleInterfaceStyle`), it should be possible to switch the `bg` value based on that. I’ll dive into this a bit more!
