# GET /orgs/{org}/settings/immutable-releases

**Resource:** [orgs](../resources/orgs.md)
**Get immutable releases settings for an organization**
**Operation ID:** `orgs/get-immutable-releases-settings`

Gets the immutable releases policy for repositories in an organization.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Immutable releases settings response |

**Success Response Schema:**

[immutable-releases-organization-settings](../schemas/immutable-releases-organization-settings/immutable-releases-organization-settings.md)

