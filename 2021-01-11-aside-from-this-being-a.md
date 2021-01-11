---
date: 2021-01-11T15:20:45.098876Z
in_reply_to: /2021/01/07/since-you-asked-heres-rebar3flamingo.html
twitter: ["https://twitter.com/jkreeftmeijer/status/1348651060215296002", "https://twitter.com/jkreeftmeijer/status/1348651061096099841"]
---
Aside from this being a very useful plugin, this was a test project to learn how to build rebar3 plugins. However, using the generator I overlooked would have done most of the work (aside from the flamingo). 🤷‍♂️

    $ rebar3 new plugin rebar3_flamingo

One thing I did figure out that might be useful in lieu of the guide I planned to write: to test a rebar3 plugin, add it to its own `project_plugins`, then symlink `_checkouts/rebar3_flamingo` back to `..`.

Now you can call `rebar3 flamingo` from its own project root.
