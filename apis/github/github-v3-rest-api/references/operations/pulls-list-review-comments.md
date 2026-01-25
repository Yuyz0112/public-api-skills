# GET /repos/{owner}/{repo}/pulls/{pull_number}/comments

**Resource:** [pulls](../resources/pulls.md)
**List review comments on a pull request**
**Operation ID:** `pulls/list-review-comments`

Lists all review comments for a specified pull request. By default, review comments
are in ascending order by ID.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github-commitcomment.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github-commitcomment.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github-commitcomment.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github-commitcomment.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `direction` | query | enum: asc, desc | No | The direction to sort results. Ignored without `sort` parameter. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [pull-request-review-comment](../schemas/pull-request-review-comment/pull-request-review-comment.md)

