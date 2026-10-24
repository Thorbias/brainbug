# brainbug
A place to hold all my thoughts about tech, gadgets and other stuff.

Published at https://thorbias.github.io/brainbug/

## Writing a new article

Create a file in `_posts/` named `YYYY-MM-DD-some-title.md` (also works directly in the GitHub web UI via *Add file → Create new file*):

```markdown
---
title: "My new article"
tags: [Coffee]
---

Text goes here.
```

Optional front matter:

- `tags: [Coffee, Mods]` – shown as chips and used for the topic filter on the landing page.
- `description: "One sentence"` – teaser on the landing page. Without it, the first words of the article are used.
- `published: false` – keeps a draft off the site.

The article appears on the landing page automatically after the next Pages build (about a minute).
A post with a future date stays hidden until that day.
