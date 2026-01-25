# DELETE /repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocked_by/{issue_id}

**Resource:** [issues](../resources/issues.md)
**Remove dependency an issue is blocked by**
**Operation ID:** `issues/remove-dependency-blocked-by`

You can use the REST API to remove a dependency that an issue is blocked by.

Removing content too quickly using this endpoint may result in secondary rate limiting.
For more information, see [Rate limits for the API](https://docs.github.com/rest/using-the-rest-api/rate-limits-for-the-rest-api#about-secondary-rate-limits)
and [Best practices for using the REST API](https://docs.github.com/rest/guides/best-practices-for-using-the-rest-api).

This endpoint supports the following custom media types. For more information, see [Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types).
- **`application/vnd.github.raw+json`**: Returns the raw Markdown body. Response will include `body`. This is the default if you do not pass a specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the Markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's Markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issue_id` | path | integer | Yes | The id of the blocking issue to remove as a dependency |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

[issue](../schemas/issue/issue.md)

