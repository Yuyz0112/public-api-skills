# POST /orgs/{org}/personal-access-tokens/{pat_id}

**Resource:** [orgs](../resources/orgs.md)
**Update the access a fine-grained personal access token has to organization resources**
**Operation ID:** `orgs/update-pat-access`

Updates the access an organization member has to organization resources via a fine-grained personal access token. Limited to revoking the token's existing access. Limited to revoking a token's existing access.

Only GitHub Apps can use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

