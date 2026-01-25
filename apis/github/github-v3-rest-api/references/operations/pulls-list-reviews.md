# GET /repos/{owner}/{repo}/pulls/{pull_number}/reviews

**Resource:** [pulls](../resources/pulls.md)
**List reviews for a pull request**
**Operation ID:** `pulls/list-reviews`

Lists all reviews for a specified pull request. The list of reviews returns in chronological order.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github-commitcomment.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github-commitcomment.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github-commitcomment.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github-commitcomment.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The list of reviews returns in chronological order. |

**Success Response Schema:**

Array of [pull-request-review](../schemas/pull-request-review/pull-request-review.md)

