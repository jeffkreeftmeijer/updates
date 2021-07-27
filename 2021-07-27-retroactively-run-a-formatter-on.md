---
date: 2021-07-27T14:27:22.671949Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/106653027045184577"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1420028038918594561"]
---
Retroactively run a formatter on past commits by using the`--exec` option during an interactive rebase:

    git rebase -i --exec 'mix format’ main
    git rebase -i --exec 'prettier --write {**/*,*}.js’ main
    git rebase -i --exec 'rubocop -a’ main

https://jeffkreeftmeijer.com/git-rebase-exec/
