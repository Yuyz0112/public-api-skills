# GET /orgs/{org}/members

**Resource:** [orgs](../resources/orgs.md)
**List organization members**
**Operation ID:** `orgs/list-members`

List all users who are members of an organization. If the authenticated user is also a member of this organization then both concealed and public members will be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: 2fa_disabled, 2fa_insecure, all | No | Filter members returned in the list. `2fa_disabled` means that only members without [two-factor authentication](https://github.com/blog/1614-two-factor-authentication) enabled will be returned. `2fa_insecure` means that only members with [insecure 2FA methods](https://docs.github.com/organizations/keeping-your-organization-secure/managing-two-factor-authentication-for-your-organization/requiring-two-factor-authentication-in-your-organization#requiring-secure-methods-of-two-factor-authentication-in-your-organization) will be returned. These options are only available for organization owners. |
| `role` | query | enum: all, admin, member | No | Filter members returned by their role. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

