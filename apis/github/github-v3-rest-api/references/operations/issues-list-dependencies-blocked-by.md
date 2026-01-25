# GET /repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocked_by

**Resource:** [issues](../resources/issues.md)
**List dependencies an issue is blocked by**
**Operation ID:** `issues/list-dependencies-blocked-by`

You can use the REST API to list the dependencies an issue is blocked by.

This endpoint supports the following custom media types. For more information, see [Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types).

- **`application/vnd.github.raw+json`**: Returns the raw Markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the Markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's Markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [issue](../schemas/issue/issue.md)

