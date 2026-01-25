# DELETE /orgs/{org}/members/{username}

**Resource:** [orgs](../resources/orgs.md)
**Remove an organization member**
**Operation ID:** `orgs/remove-member`

Removing a user from this list will remove them from all teams and they will no longer have any access to the organization's repositories.

> [!NOTE]
> If a user has both direct membership in the organization as well as indirect membership via an enterprise team, only their direct membership will be removed. Their indirect membership via an enterprise team remains until the user is removed from the enterprise team.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |

