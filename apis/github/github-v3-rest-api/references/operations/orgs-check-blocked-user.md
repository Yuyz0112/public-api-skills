# GET /orgs/{org}/blocks/{username}

**Resource:** [orgs](../resources/orgs.md)
**Check if a user is blocked by an organization**
**Operation ID:** `orgs/check-blocked-user`

Returns a 204 if the given user is blocked by the given organization. Returns a 404 if the organization is not blocking the user, or if the user account has been identified as spam by GitHub.

## Responses

| Status | Description |
|--------|-------------|
| 204 | If the user is blocked |
| 404 | If the user is not blocked |

