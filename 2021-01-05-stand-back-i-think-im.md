---
date: 2021-01-05T15:57:42.138967Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105503933194295189"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1346486032276090882"]
---
Stand back, I think I’m building another static site generator.

    generate:
    	erb inner="$(shell cat index.html)" layout.html.erb > _output/index.html
