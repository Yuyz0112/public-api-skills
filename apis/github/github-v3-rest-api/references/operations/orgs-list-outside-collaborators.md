# GET /orgs/{org}/outside_collaborators

**Resource:** [orgs](../resources/orgs.md)
**List outside collaborators for an organization**
**Operation ID:** `orgs/list-outside-collaborators`

List all users who are outside collaborators of an organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: 2fa_disabled, 2fa_insecure, all | No | Filter the list of outside collaborators. `2fa_disabled` means that only outside collaborators without [two-factor authentication](https://github.com/blog/1614-two-factor-authentication) enabled will be returned. `2fa_insecure` means that only outside collaborators with [insecure 2FA methods](https://docs.github.com/organizations/keeping-your-organization-secure/managing-two-factor-authentication-for-your-organization/requiring-two-factor-authentication-in-your-organization#requiring-secure-methods-of-two-factor-authentication-in-your-organization) will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

