# PUT /orgs/{org}/blocks/{username}

**Resource:** [orgs](../resources/orgs.md)
**Block a user from an organization**
**Operation ID:** `orgs/block-user`

Blocks the given user on behalf of the specified organization and returns a 204. If the organization cannot block the given user a 422 is returned.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 422 | (reference) |

