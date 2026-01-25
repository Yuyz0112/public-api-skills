# PATCH /gists/{gist_id}

**Resource:** [gists](../resources/gists.md)
**Update a gist**
**Operation ID:** `gists/update`

Allows you to update a gist's description and to update, delete, or rename gist files. Files
from the previous version of the gist that aren't explicitly changed during an edit
are unchanged.

At least one of `description` or `files` is required.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown. This is the default if you do not pass any specific media type.
- **`application/vnd.github.base64+json`**: Returns the base64-encoded contents. This can be useful if your gist contains any invalid UTF-8 sequences.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[gist-simple](../schemas/gist-simple/gist-simple.md)

