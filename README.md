<p align="center">
    <img src="static/oxo.icon.webp" alt="" width="200px" />
</p>

---

<p align="center">
    <img src="static/oxo.logo.webp" alt="oxo" width="300px" />
</p>

---

<p align="center">
    an activity journal for <a href="https://github.com/rri/oxoxo" title="oxo">oxo</a> development
</p>

---

This repository contains the source code and content of my activity journal for the development of
[oxo](https://github.com/rri/oxoxo). Content created or updated in this repository gets published
automatically to my [activity journal](https://oxo-lang.org).

To create a new post, you must:

- Become a collaborator on this repository.
- Clone the repository.
- Create a new Markdown file [1] in the `content` directory.
- Provide the necessary frontmatter in the new Markdown file.
- Provide the content of the new post.
- Validate [2] a draft of the new post.
- Commit and push the change to GitHub.

[1] The new Markdown file should have content that looks like the template below. Anything in braces
is a placeholder and must be replaced. You may have more than 1 author and any number of tags (even
zero).

```
+++
title = "{TITLE}"
date = {YYYY}-{MM}-{DD}
[taxonomies]
authors = ["{AUTHOR-1}", "{AUTHOR-2}"]
tags = ["{TAG-1}", "{TAG-2}"]
+++

{CONTENT}
```

[2] To validate a draft, you need to install [Zola](https://getzola.org) locally and run its server. On a macOS system, you can follow these steps:

- Run `brew install zola`.
- In the repository root, run `zola serve`.

In case you want to set up a *new* static website just like silentYak, you may do so by following
the [(very brief) instructions here](https://optimix.dev/2023/12/23/static-website/).
