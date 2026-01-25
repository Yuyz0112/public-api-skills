# POST /markdown

**Resource:** [markdown](../resources/markdown.md)
**Render a Markdown document**
**Operation ID:** `markdown/render`

Depending on what is rendered in the Markdown, you may need to provide additional token scopes for labels, such as `issues:read` or `pull_requests:read`.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

