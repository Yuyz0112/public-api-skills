# GET /repos/{owner}/{repo}/pulls/{pull_number}/files

**Resource:** [pulls](../resources/pulls.md)
**List pull requests files**
**Operation ID:** `pulls/list-files`

Lists the files in a specified pull request.

> [!NOTE]
> Responses include a maximum of 3000 files. The paginated response returns 30 files per page by default.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |
| 500 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [diff-entry](../schemas/diff-entry/diff-entry.md)

