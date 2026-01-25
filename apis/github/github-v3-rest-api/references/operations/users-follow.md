# PUT /user/following/{username}

**Resource:** [users](../resources/users.md)
**Follow a user**
**Operation ID:** `users/follow`

Note that you'll need to set `Content-Length` to zero when calling out to this endpoint. For more information, see "[HTTP verbs](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#http-method)."

OAuth app tokens and personal access tokens (classic) need the `user:follow` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

