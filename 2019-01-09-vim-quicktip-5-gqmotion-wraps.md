---
date: 2019-01-09T14:03:39.474907Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/101386985058361360", "https://mastodon.social/@jkreeftmeijer/101386985088963724"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1083001349082701824", "https://twitter.com/jkreeftmeijer/status/1083001350076727303"]
tags: ["vim"]
---
Vim quicktip #5: `gq{motion}` wraps lines to fit the configured textwidth (`:set textwidth`). If textwidth is not set, #vim will use the screen width (with a maximum of 79).

Use `gqq` to format the current line, or `gq` in visual select mode to format all selected lines.

This is especially useful to make sure the lines in your commit messages aren’t longer than 72 characters. [vim-fugitive](https://github.com/tpope/vim-fugitive) automatically sets the textwidth option to 72 when writing a commit message with `:Gcommit`.
