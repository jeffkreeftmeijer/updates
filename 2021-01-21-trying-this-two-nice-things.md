---
date: 2021-01-21T15:20:46.483617Z
in_reply_to: /2021/01/21/an-idea-instead-of-listing.html
twitter: ["https://twitter.com/jkreeftmeijer/status/1352275059189145603"]
mastodon: ["https://mastodon.social/@jkreeftmeijer/105594388841688458"]
---
Trying this. Two nice things about this `make test` task:

1. I don’t need to know which command runs the tests in this project. That’s an implementation detail.

2. It runs formatting checks whenever tests are run locally (as formatting errors break CI)

https://github.com/jeffkreeftmeijer/shine/blob/ad49421f27c063729c8f438d2b5ca9838ea9584e/Makefile#L1-L4
