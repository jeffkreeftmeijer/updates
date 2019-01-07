---
date: 2019-01-07T15:15:06.715182Z
in_reply_to: /2019/01/07/disclaimer-i-dont-like-tap.html
mastodon: ["https://mastodon.social/@jkreeftmeijer/101375941425995620"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1082294557117693952", "https://twitter.com/jkreeftmeijer/status/1082294558250143745"]
---
I’d love to see better examples of using `#tap`, but I’ve mostly seen it used to refactor this:

    metadata = {}
    metadata[:id] = user.id if user
    metadata

That’s explicit. It creates a hash, adds a value if a condition is true, then returns the hash.

With `#tap`, the code is more difficult to read, and requires the next person to know what `#tap` does (“yields x to the block, and then returns x.”). 🤷‍♀️

    {}.tap do |metadata|
      metadata[:id] = user.id if user
    end
