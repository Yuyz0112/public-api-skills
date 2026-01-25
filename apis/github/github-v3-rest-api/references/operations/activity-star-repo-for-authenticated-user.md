# PUT /user/starred/{owner}/{repo}

**Resource:** [activity](../resources/activity.md)
**Star a repository for the authenticated user**
**Operation ID:** `activity/star-repo-for-authenticated-user`

Note that you'll need to set `Content-Length` to zero when calling out to this endpoint. For more information, see "[HTTP method](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#http-method)."

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

