# GET /orgs/{org}/actions/oidc/customization/sub

**Resource:** [oidc](../resources/oidc.md)
**Get the customization template for an OIDC subject claim for an organization**
**Operation ID:** `oidc/get-oidc-custom-sub-template-for-org`

Gets the customization template for an OpenID Connect (OIDC) subject claim.

OAuth app tokens and personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | A JSON serialized template for OIDC subject claim customization |

**Success Response Schema:**

[oidc-custom-sub](../schemas/oidc-custom-sub/oidc-custom-sub.md)

