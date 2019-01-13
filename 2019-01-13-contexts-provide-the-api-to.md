---
date: 2019-01-13T10:13:39.082531Z
in_reply_to: https://twitter.com/jvanbaarsen/status/1084162402843848704
twitter: ["https://twitter.com/jkreeftmeijer/status/1084393020173312000", "https://twitter.com/jkreeftmeijer/status/1084393020705914881", "https://twitter.com/jkreeftmeijer/status/1084393021200891904"]
---
@jvanbaarsen@twitter.com Contexts provide the API to interact with your schemas to keep knowledge about your repository out of the rest of your app. 

While they can group functions for multiple schemas together (like in the Accounts example), you’re encouraged to start with one context per schema if it’s not immediately clear what the groups could be.

For now, I’d call the context for the Recipe schema “Recipes”.  Eventually, that context might manage both recipe and ingredient data, and you could have an Accounts context for handling users and their credentials, for example.
