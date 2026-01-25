# GET /orgs/{org}/members/{username}

**Resource:** [orgs](../resources/orgs.md)
**Check organization membership for a user**
**Operation ID:** `orgs/check-membership-for-user`

Check if a user is, publicly or privately, a member of the organization.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if requester is an organization member and user is a member |
| 302 | Response if requester is not an organization member |
| 404 | Not Found if requester is an organization member and user is not a member |

