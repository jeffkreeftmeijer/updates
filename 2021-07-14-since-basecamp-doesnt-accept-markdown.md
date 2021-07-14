---
date: 2021-07-14T13:48:09.457139Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/106579262756604796", "https://mastodon.social/@jkreeftmeijer/106579262777408099"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1415307122531786756", "https://twitter.com/jkreeftmeijer/status/1415307123236421634"]
---
Since Basecamp doesn’t accept Markdown anymore, what’s the best way to get a piece of text written elsewhere (which might include links and subheadings) imported into it?


Here’s a slightly cumbersome option. Trix (Basecamp’s editor) uses a `contenteditable` block, which retains styling. That means one could convert their comment to HTML (like the preview in a Markdown editor), copy the text from the rendered page, and paste it into Basecamp.
