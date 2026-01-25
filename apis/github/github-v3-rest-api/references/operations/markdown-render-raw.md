# POST /markdown/raw

**Resource:** [markdown](../resources/markdown.md)
**Render a Markdown document in raw mode**
**Operation ID:** `markdown/render-raw`

You must send Markdown as plain text (using a `Content-Type` header of `text/plain` or `text/x-markdown`) to this endpoint, rather than using JSON format. In raw mode, [GitHub Flavored Markdown](https://github.github.com/gfm/) is not supported and Markdown will be rendered in plain format like a README.md file. Markdown content must be 400 KB or less.

## Request Body

**Content Types:** `text/plain`, `text/x-markdown`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

