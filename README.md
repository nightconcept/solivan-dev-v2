# solivan-dev-v2

Personal website and blog using [Hugo](https://gohugo.io/) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod). I switched in March 2024 from SvelteKit based solivan-dev for reasons that will be encapsulated in a future blog post.

## Usage

Build site:
```
hugo
```

Make a new post (creates a new Markdown file in designated folder using archetypes/default.md as a template):
```
hugo new blog/post.md
```

Commit to post (successful commit to GitHub should result in a new deployment):
```
// If hook was changed or not already setup before in that repo
pre-commit install

pre-commit
```

## Inspirations

A mashup of several tutorials and repos, but these in particular:

- [Building a website using Hugo + PaperMod | Kunyang's Blog](https://kyxie.github.io/en/blog/tech/papermod/)
- [Getting set up in Hugo | CloudCannon](https://cloudcannon.com/tutorials/hugo-beginner-tutorial/)
- [Quick start | Hugo](https://gohugo.io/getting-started/quick-start/)
