---
date: 2019-06-13T15:00:30.222988Z
in_reply_to: https://twitter.com/petecorey/status/1139182470585233408
twitter: ["https://twitter.com/jkreeftmeijer/status/1139185777798242305"]
---
@petecorey@twitter.com I'm using [a list with an element for each position on the board](https://github.com/jeffkreeftmeijer/hayago/blob/master/lib/hayago/state.ex#L30). Whenever a stone is placed, I `List.replace_at` to replace the default `nil` value with either `:black` or `:white`. :)
