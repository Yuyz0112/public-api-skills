# PUT /orgs/{org}/actions/oidc/customization/sub

**Resource:** [oidc](../resources/oidc.md)
**Set the customization template for an OIDC subject claim for an organization**
**Operation ID:** `oidc/update-oidc-custom-sub-template-for-org`

Creates or updates the customization template for an OpenID Connect (OIDC) subject claim.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [oidc-custom-sub](../schemas/oidc-custom-sub/oidc-custom-sub.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Empty response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

