---
date: 2018-12-13T23:39:24Z
mastodon: https://mastodon.social/@jkreeftmeijer/101236371751163533
---
I can't seem to find how to post a response to a status on another instance via the Mastodon API.

Passing the ID as the `in_reply_to_id` parameter produces a 404 because the status can't be found. That makes some sense, as that status isn't on the instance I'm calling out to (right?). Switching the API base URL to the other instance gives me a 401, because I don't have an API app set up there.

What am I missing here? Any pointers would be greatly appreciated.
