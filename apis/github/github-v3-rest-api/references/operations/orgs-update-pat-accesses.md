# POST /orgs/{org}/personal-access-tokens

**Resource:** [orgs](../resources/orgs.md)
**Update the access to organization resources via fine-grained personal access tokens**
**Operation ID:** `orgs/update-pat-accesses`

Updates the access organization members have to organization resources via fine-grained personal access tokens. Limited to revoking a token's existing access.

Only GitHub Apps can use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

