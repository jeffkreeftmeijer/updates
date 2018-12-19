---
date: 2018-12-19T19:17:30Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/101269305663212420", "https://mastodon.social/@jkreeftmeijer/101269466770479191"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1075469905586212869", "https://twitter.com/jkreeftmeijer/status/1075480307879591936", "https://twitter.com/jkreeftmeijer/status/1075480355895955456"]
---
Started <https://updates.jeffkreeftmeijer.com> as a first step to being sure my published update/photo backlog isn't lost if for some reason Twitter stops allowing me to download my archive, my Mastodon instance falls over, or my old image service finally decides to kick the bucket.


Currently, it involves writing updates as markdown files, then passing the file to a local script that does some conversion and posts it on Mastodon. Non-replies are then crossposted to Twitter from there.

Ideally, this would have a posting interface that pushes markdown files to a git repository, which has hooks to convert and syndicate each update to the correct location, depending on its contents and what it replies to, for example.
