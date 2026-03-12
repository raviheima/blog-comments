# blog-comments

This repository stores blog post comments powered by [giscus](https://giscus.app) — a commenting system built on [GitHub Discussions](https://docs.github.com/en/discussions).

## How it works

Each blog post maps to a GitHub Discussion in this repository. Visitors can leave comments on a blog post using their GitHub account, and those comments are stored as GitHub Discussion replies here.

## Setup

To use this repository with giscus:

1. **Enable GitHub Discussions** in this repository's settings (`Settings → General → Features → Discussions`).
2. **Install the giscus GitHub App** for this repository: [github.com/apps/giscus](https://github.com/apps/giscus).
3. **Configure giscus** for your blog by visiting [giscus.app](https://giscus.app), selecting this repository, and copying the generated `<script>` snippet into your blog's comment section.

## Configuration example

```html
<script src="https://giscus.app/client.js"
        data-repo="raviheima/blog-comments"
        data-repo-id="YOUR_REPO_ID"
        data-category="Announcements"
        data-category-id="YOUR_CATEGORY_ID"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>
```

Replace `YOUR_REPO_ID` and `YOUR_CATEGORY_ID` with the values generated on [giscus.app](https://giscus.app).
