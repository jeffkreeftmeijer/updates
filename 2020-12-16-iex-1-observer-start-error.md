---
date: 2020-12-16T13:04:06.321635Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105390004369539397"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1339194586841878529"]
---
    iex(1)> :observer.start  
    [error] ERROR: Could not find 'wxe_driver.so' in: /Users/jeffkreeftmeijer/.asdf/installs/[…]

The observer needs wxwidgets. Check with `wx-config --version`, install on macOS with `brew install wxmac`, then reinstall Erlang. #elixirquicktips
