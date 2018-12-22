---
date: 2018-12-22T11:24:28Z
in_reply_to: https://twitter.com/chastell/status/1076046784542183424
twitter: https://twitter.com/jkreeftmeijer/status/1076438296782426112
---
@chastell@twitter.com Also, the `autowrite` and `autowriteall` options save the file when switching buffers or quitting, which covers cases where the file is changed without switching modes.

Ideally, it'd just save whenever `&modified` is 1, but I haven't found a way to hook in yet. 🤔
