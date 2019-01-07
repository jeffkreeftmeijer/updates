---
date: 2019-01-07T22:23:41.232199Z
in_reply_to: https://ruby.social/@judofyr/101376898394628518
mastodon: ["https://mastodon.social/@jkreeftmeijer/101377626622425594"]
---
@judofyr@ruby.social Got it working for Twitter by forcing the encoding to UTF-8, and running JSON responses through `JSON.parse` instead of whatever it did before.

It seems to have great provider support, but I’m getting Twitter’s unparsed HTML response (with that javascript tag), which is to be expected, actually. I’ll check how Mastodon does this—as it seems to only get the tweet content—sometime soon. Thanks for your help! :)
