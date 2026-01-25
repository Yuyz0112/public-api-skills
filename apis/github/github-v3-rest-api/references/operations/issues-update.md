# PATCH /repos/{owner}/{repo}/issues/{issue_number}

**Resource:** [issues](../resources/issues.md)
**Update an issue**
**Operation ID:** `issues/update`

Issue owners and users with push access or Triage role can edit an issue.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 410 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[issue](../schemas/issue/issue.md)

