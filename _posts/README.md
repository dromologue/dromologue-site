# Blog posts

Drop a Markdown file in this directory and it becomes a page on the site,
listed automatically in the left-hand Notes menu and on `/blog/`.

## Naming

    _posts/YYYY-MM-DD-a-short-slug.md

The date prefix is required by Jekyll and sets the post date and ordering.
The slug after the date becomes the URL, e.g. `/a-short-slug/`.

## Front matter

Only a title is needed; the layout is applied automatically.

    ---
    title: The title of the post
    ---

    Your first paragraph here. The first paragraph is used as the excerpt
    on the blog index.

You can override the displayed date with a `date:` line if you want it to
differ from the filename.

## Style

Posts are prose, British English. Per the brand reference
(`Brand/ref_brand_sheet.png`), headings separate with a colon, never a dash;
in-sentence dashes become commas.

This README is ignored by the build (it has no front matter, so Jekyll
treats it as a static file and `_posts/*.md` without front matter is not
rendered as a post).
