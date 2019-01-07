---
date: 2019-01-07T19:25:31.017319Z
in_reply_to: https://twitter.com/benediktdeicke/status/1082353589044027392
twitter: ["https://twitter.com/jkreeftmeijer/status/1082357576052953089"]
---
@benediktdeicke@twitter.com That’s a great example I didn’t think of. I usually still do that in two lines:

    irb> model.save
    => true
    irb> model.errors
    => []

But I’ll try to remember to use `#tap` there. It’s just not top of mind for me. 🤷‍♀️
