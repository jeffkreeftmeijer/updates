---
date: 2021-08-06T19:21:35.068439Z
in_reply_to: https://twitter.com/haarts/status/1423724269842968577
twitter: ["https://twitter.com/jkreeftmeijer/status/1423725954657103877", "https://twitter.com/jkreeftmeijer/status/1423725955261009926"]
---
@haarts@twitter.com Oh, you and me both. 

Depending on your throughput and reliability needs, you might get away with a loop that takes jobs from a queue and just runs them in a single process. 🤔

Assuming this is Ruby, you could even retry them using the built-in `retry` keyword and make it quite elegant.
