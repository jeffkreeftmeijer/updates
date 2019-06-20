---
date: 2019-06-20T18:02:48.448259Z
mastodon: ["https://mastodon.social/@jkreeftmeijer/102305219702394938", "https://mastodon.social/@jkreeftmeijer/102305219740556926"]
twitter: ["https://twitter.com/jkreeftmeijer/status/1141768367029796864", "https://twitter.com/jkreeftmeijer/status/1141768367856111616", "https://twitter.com/jkreeftmeijer/status/1141768368774664195"]
---
My current article series is based around writing an example application. As an experiment, I’m writing most of the draft in [~250-word commit messages in the example repository](https://github.com/jeffkreeftmeijer/hayago/commits/master).

To get a very rough outline for the first article, I printed the commit message bodies to a markdown file in reverse.

    $ git log --reverse --pretty=format:%b > draft.md

The outline was a good starting point to write the story. It felt more efficient, as the work was split between prototyping and explaining code, and writing and editing an article. Plus, the example repository now has well-groomed commits and good explanations of all changes. 🙌
