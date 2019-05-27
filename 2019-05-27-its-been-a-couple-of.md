---
date: 2019-05-27T12:25:34.326212Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/102167998216360611"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1132986192545427457", "https://twitter.com/jkreeftmeijer/status/1132986193400999937"]
---
It’s been a couple of years, so I’m giving [Dash](https://kapeli.com/dash) another shot. I can’t remember why it didn’t stick before, but I’m really liking it so far. Any tips I should know about?

Here’s my first tip: I’d prefer to use a smart way to read its documentation bundles from the terminal directly, but this bash function will do for now. Type `d Enum.map` to activate Dash and start a search.

    function d() {
      open "dash://$@"
    }
