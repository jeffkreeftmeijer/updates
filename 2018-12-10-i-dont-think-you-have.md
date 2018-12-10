---
date: 2018-12-10T11:52:00Z
in_reply_to: https://twitter.com/chrisheithoff/status/1072095495533854720
twitter: https://twitter.com/jkreeftmeijer/status/1072096736280231937
---
@chrisheithoff@twitter.com I don't think you have to, as matchit.vim is included in Vim itself since 6.0. Your language plugin should set `b:match_words` for files of the correct type, so `:echo b:match_words` should return a list of match words if everything's set up correctly.
