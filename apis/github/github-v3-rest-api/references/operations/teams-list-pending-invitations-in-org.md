# GET /orgs/{org}/teams/{team_slug}/invitations

**Resource:** [teams](../resources/teams.md)
**List pending team invitations**
**Operation ID:** `teams/list-pending-invitations-in-org`

The return hash contains a `role` field which refers to the Organization Invitation role and will be one of the following values: `direct_member`, `admin`, `billing_manager`, `hiring_manager`, or `reinstate`. If the invitee is not a GitHub member, the `login` field in the return hash will be `null`.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}/invitations`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [organization-invitation](../schemas/organization-invitation/organization-invitation.md)

