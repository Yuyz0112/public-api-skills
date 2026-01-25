# GET /orgs/{org}/failed_invitations

**Resource:** [orgs](../resources/orgs.md)
**List failed organization invitations**
**Operation ID:** `orgs/list-failed-invitations`

The return hash contains `failed_at` and `failed_reason` fields which represent the time at which the invitation failed and the reason for the failure.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [organization-invitation](../schemas/organization-invitation/organization-invitation.md)

