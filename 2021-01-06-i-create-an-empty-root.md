---
date: 2021-01-06T12:08:52.480446Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105508695714095410"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1346790831181672448"]
---
I create an empty root commit whenever I start a new git repository to allow me to rebase up to the first actual change. I almost never have to do that, but it’s great to have if I do.

    $ git commit --allow-empty -m "$ git init"

