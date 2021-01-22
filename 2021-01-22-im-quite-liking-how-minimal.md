---
date: 2021-01-22T21:14:35.140126Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105601438508130284"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1352726372557455366"]
---
I’m quite liking how minimal Gleam’s `gleam/otp/actor` is. Having a single function that returns a `Continue` or `Stop` tuple clearly reveals how keeping state is just a loop in a process.

https://github.com/jeffkreeftmeijer/shine/blob/stats/src/shine/reporter.gleam
