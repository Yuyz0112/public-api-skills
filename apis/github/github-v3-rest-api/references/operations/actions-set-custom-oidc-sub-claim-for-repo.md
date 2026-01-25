# PUT /repos/{owner}/{repo}/actions/oidc/customization/sub

**Resource:** [actions](../resources/actions.md)
**Set the customization template for an OIDC subject claim for a repository**
**Operation ID:** `actions/set-custom-oidc-sub-claim-for-repo`

Sets the customization template and `opt-in` or `opt-out` flag for an OpenID Connect (OIDC) subject claim for a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Empty response |
| 400 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

