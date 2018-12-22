---
date: 2018-12-22T17:37:47Z
in_reply_to: https://www.reddit.com/r/vim/comments/a1irnz/consistent_terminal_colors_with_16ansicolor_vim/ec9hg1q/
reddit: https://www.reddit.com/r/vim/comments/a1irnz/consistent_terminal_colors_with_16ansicolor_vim/ecbxaee/
---
Congratulations on your first plugin! It might be nice to check the interface style on `BufEnter`, so you can switch to dark mode and have Vim switch the background even if it was already open.

I [checked](https://twitter.com/jkreeftmeijer/status/1075358088914452480) how the darkmode-aware background colors worked the other day, and it seems to be an application default. In custom themes, the only way I found to get toggling background colors is not to configure any. I'll try doing that in my theme, to see if that'd still look good, sometime soon.

For glare, I usually switch to the light version of my [terminal theme](https://github.com/jeffkreeftmeijer/appsignal.terminal). Since Dim uses the same syntax colors for dark and light backgrounds, that just means swapping the text and background colors. I think the easiest way to get a higher contrast would be to use a higher contrast terminal theme.
