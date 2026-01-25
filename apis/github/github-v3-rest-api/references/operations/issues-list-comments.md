# GET /repos/{owner}/{repo}/issues/{issue_number}/comments

**Resource:** [issues](../resources/issues.md)
**List issue comments**
**Operation ID:** `issues/list-comments`

You can use the REST API to list comments on issues and pull requests. Every pull request is an issue, but not every issue is a pull request.

Issue comments are ordered by ascending ID.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [issue-comment](../schemas/issue-comment/issue-comment.md)

