---
date: 2018-12-21T09:45:00Z
in_reply_to: https://twitter.com/jvanbaarsen/status/1076013026040516609
twitter: https://twitter.com/jkreeftmeijer/status/1076051075210326017
---
@jvanbaarsen@twitter.com In that category; my `,s` and `,S` both pre-fill the ex command with `:%s///`, but the former places the cursor in the search pattern, and the later in the replacement.

    nnoremap ,s :%s///<left><left>
    vnoremap ,s :s///<left><left>
    nnoremap ,S :%s///<left>
    vnoremap ,S :s///<left>
