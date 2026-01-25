# GET /orgs/{org}/invitations

**Resource:** [orgs](../resources/orgs.md)
**List pending organization invitations**
**Operation ID:** `orgs/list-pending-invitations`

The return hash contains a `role` field which refers to the Organization
Invitation role and will be one of the following values: `direct_member`, `admin`,
`billing_manager`, or `hiring_manager`. If the invitee is not a GitHub
member, the `login` field in the return hash will be `null`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `role` | query | enum: all, admin, direct_member... | No | Filter invitations by their member role. |
| `invitation_source` | query | enum: all, member, scim | No | Filter invitations by their invitation source. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [organization-invitation](../schemas/organization-invitation/organization-invitation.md)

