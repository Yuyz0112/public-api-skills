# GET /orgs/{org}/invitations/{invitation_id}/teams

**Resource:** [orgs](../resources/orgs.md)
**List organization invitation teams**
**Operation ID:** `orgs/list-invitation-teams`

List all teams associated with an invitation. In order to see invitations in an organization, the authenticated user must be an organization owner.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

