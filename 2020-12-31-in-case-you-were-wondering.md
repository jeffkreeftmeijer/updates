---
date: 2020-12-31T14:34:15.312032Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105475293512426611"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1344653080168697864"]
---
In case you were wondering if you can run PropEr on Gleam (as I was); yes you can, by patching rebar3_proper to accept `.gleam` files and importing external functions from `proper` and `proper_types`.

https://github.com/jeffkreeftmeijer/proper_gleam_example/blob/master/test/prop_proper_gleam_example.gleam

![Terminal output showing PropEr running](/media/Screen Shot 2020-12-31 at 12.56.28.png)
