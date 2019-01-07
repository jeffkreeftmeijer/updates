---
date: 2019-01-07T19:17:46.834124Z
in_reply_to: https://ruby.social/@judofyr/101376662329228714
mastodon: ["https://mastodon.social/@jkreeftmeijer/101376895644503916"]
---
@judofyr@ruby.social That’s a better example indeed. Instead of preventing an explicit return like in my example, this prevents having to store the result in a variable. But, exactly, I’d still prefer that.

    result = do_stuff
    result.is_admin = true
    foo(result)
