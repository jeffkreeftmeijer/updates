---
date: 2018-12-10T14:17:46Z
in_reply_to: https://twitter.com/chrisheithoff/status/1072126468891697152
twitter: https://twitter.com/jkreeftmeijer/status/1072134419031515136
---
@chrisheithoff@twitter.com I didn't, but you're absolutely right. It's in `$VIMRUNTIME/plugin/matchit.vim` in neovim 0.3.1, which loads it by default (`:echo exists("loaded_matchit")` returns 1) while Vim 8 doesn't. Like you said, it needs to be explicitly loaded with `:packadd! matchit`.

