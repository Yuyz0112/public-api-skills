# GET /repos/{owner}/{repo}/actions/oidc/customization/sub

**Resource:** [actions](../resources/actions.md)
**Get the customization template for an OIDC subject claim for a repository**
**Operation ID:** `actions/get-custom-oidc-sub-claim-for-repo`

Gets the customization template for an OpenID Connect (OIDC) subject claim.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Status response |
| 400 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[oidc-custom-sub-repo](../schemas/oidc-custom-sub-repo/oidc-custom-sub-repo.md)

