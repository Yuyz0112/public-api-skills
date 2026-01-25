# POST /gists/{gist_id}/comments

**Resource:** [gists](../resources/gists.md)
**Create a gist comment**
**Operation ID:** `gists/create-comment`

Creates a comment on a gist.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown. This is the default if you do not pass any specific media type.
- **`application/vnd.github.base64+json`**: Returns the base64-encoded contents. This can be useful if your gist contains any invalid UTF-8 sequences.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[gist-comment](../schemas/gist-comment/gist-comment.md)

