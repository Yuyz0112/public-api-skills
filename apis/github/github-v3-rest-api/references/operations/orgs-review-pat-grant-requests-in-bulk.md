# POST /orgs/{org}/personal-access-token-requests

**Resource:** [orgs](../resources/orgs.md)
**Review requests to access organization resources with fine-grained personal access tokens**
**Operation ID:** `orgs/review-pat-grant-requests-in-bulk`

Approves or denies multiple pending requests to access organization resources via a fine-grained personal access token.

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

