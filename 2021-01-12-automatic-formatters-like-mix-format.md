---
date: 2021-01-12T16:17:53.064659Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105543648699008679", "https://mastodon.social/@jkreeftmeijer/105543648722095801"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1349027823139364864", "https://twitter.com/jkreeftmeijer/status/1349027823919443971"]
---
Automatic formatters like `mix format` move discussions about coding style to the implementers of the formatter or language, which is where those should be.

They also rid you of having to reformat code yourself. Type code, run the formatter (automatically), commit. Done.


Enforce a format by adding a check to CI, even if you don’t fully agree with its rules. That way, you at least _have_ a format. If you really care, configure it.

Case in point: I dislike `rebar3_format`’s indentation rules, for example (https://github.com/jeffkreeftmeijer/shine/blob/main/src/rebar3_shine.erl). 🤷‍♂️
