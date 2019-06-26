---
date: 2019-06-26T12:49:11.324517Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/102337960397935423"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1143863772710354945", "https://twitter.com/jkreeftmeijer/status/1143863773448593408"]
---
Deploying a branch that’s not called `master` to Heroku (or pushing to a different branch name on remote in general)? Remembering to prefix the remote’s branch name with the local one might save you some confusion.

    $ git push heroku my_branch:master

Where `heroku` is the remote, `my_branch` is the local branch name, and `master` is the remote branch name. Hopefully, I’ll get it right on the first try too, one day.
