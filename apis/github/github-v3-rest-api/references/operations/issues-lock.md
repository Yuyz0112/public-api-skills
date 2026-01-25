# PUT /repos/{owner}/{repo}/issues/{issue_number}/lock

**Resource:** [issues](../resources/issues.md)
**Lock an issue**
**Operation ID:** `issues/lock`

Users with push access can lock an issue or pull request's conversation.

Note that, if you choose not to pass any parameters, you'll need to set `Content-Length` to zero when calling out to this endpoint. For more information, see "[HTTP method](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#http-method)."

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 410 | (reference) |
| 422 | (reference) |

