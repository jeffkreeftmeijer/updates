---
date: 2021-01-21T14:15:20.408461Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105594127651298234"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1352258475716448256"]
---
An idea: instead of listing commands in your README, provide a Makefile in your project root:

- `make setup` installs dependencies
- `make test` runs the test suite (also on CI)
- `make server` starts the app
- `make format` formats your code
- `make deploy` publishes releases
