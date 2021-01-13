---
date: 2021-01-13T16:22:04.039976Z
in_reply_to: https://twitter.com/daxhuiberts/status/1349386201090969605
twitter: ["https://twitter.com/jkreeftmeijer/status/1349391264509255681"]
---
@daxhuiberts@twitter.com If you’re only interested in errors, I’d use something like this over passing the current span into the spawned process. 👍

I’d investigate having the task crash, and catching the error in the main process, though. That should save you a result-tuple.
