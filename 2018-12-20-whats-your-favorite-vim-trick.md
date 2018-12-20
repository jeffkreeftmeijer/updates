---
date: 2018-12-20T15:48:35Z
title: What's your favorite Vim trick?
canonical_url: https://updates.jeffkreeftmeijer.com/2018/12/20/whats-your-facorite-vim-trick.html
tags: #vim #editor #terminal
twitter: ["https://twitter.com/jkreeftmeijer/status/1075780054771060736", "https://twitter.com/jkreeftmeijer/status/1075780055907725312"]
mastodon: https://mastodon.social/@jkreeftmeijer/101274151535803946
dev_to: https://dev.to/jkreeftmeijer/whats-your-favorite-vim-trick-5eag
---
What's that Vim trick that blew your mind the first time you learned about it?  A feature that has a big (or small) impact on your workflow, or just a command you use a lot. Anything goes! 🤯

I'll start with my go-to trick: I usually only notice a match should be replaced after searching for it with `/` (`/foo`). After learning that substitutions with empty search patterns (`%:s//bar/`) replace the previously found matches, I've never had to re-type a pattern again.
