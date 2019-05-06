---
date: 2019-05-06T12:11:56.112185Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/102049036088120863"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1125372616146026496"]
---
Here’s a sneak peek at my upcoming book named “Technical editing with Vim substitutions”, which shows removing trailing periods from markdown lists:

    :%s/\(\(-\|*\|\d*\.\) .\+\)./\1/

