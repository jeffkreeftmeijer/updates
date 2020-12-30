---
date: 2020-12-30T09:46:53.732814Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/105468501252858983"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1344218387979915264", "https://twitter.com/jkreeftmeijer/status/1344218388495802370"]
---
Any tips to checking coc.vim plugins into dotfiles repositories? The plugin manager (`:CocInstall`) is great, but I’d like to be able to install my whole setup in as few steps as possible in the future, so I’d prefer not to have to remember to install these separately.

From my investigation so far, it looks like I’ll have to check the coc data directory in, then .gitignore everything but package.json, then`npm install` them after checking out my dotfiles on a new machine.
