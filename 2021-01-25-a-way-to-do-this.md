---
date: 2021-01-25T14:50:13.039578Z
in_reply_to: /2021/01/25/vim-users-whats-your-favorite.html
twitter: ["https://twitter.com/jkreeftmeijer/status/1353716806050000899"]
---
A way to do this would be adding an `autocmd` that calls out to `defaults read -g AppleInterfaceStyle` and updates the `bg` value if needed. 

I might wrap that in a plugin if it doesn’t exist yet.
