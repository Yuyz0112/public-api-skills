# PUT /orgs/{org}/public_members/{username}

**Resource:** [orgs](../resources/orgs.md)
**Set public organization membership for the authenticated user**
**Operation ID:** `orgs/set-public-membership-for-authenticated-user`

The user can publicize their own membership. (A user cannot publicize the membership for another user.)

Note that you'll need to set `Content-Length` to zero when calling out to this endpoint. For more information, see "[HTTP method](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#http-method)."

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |

