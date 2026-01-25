# GET /orgs/{org}/public_members/{username}

**Resource:** [orgs](../resources/orgs.md)
**Check public organization membership for a user**
**Operation ID:** `orgs/check-public-membership-for-user`

Check if the provided user is a public member of the organization.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if user is a public member |
| 404 | Not Found if user is not a public member |

