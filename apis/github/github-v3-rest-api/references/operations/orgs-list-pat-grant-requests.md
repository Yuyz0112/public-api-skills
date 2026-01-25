# GET /orgs/{org}/personal-access-token-requests

**Resource:** [orgs](../resources/orgs.md)
**List requests to access organization resources with fine-grained personal access tokens**
**Operation ID:** `orgs/list-pat-grant-requests`

Lists requests from organization members to access organization resources with a fine-grained personal access token.

Only GitHub Apps can use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [organization-programmatic-access-grant-request](../schemas/organization-programmatic-access-grant-request/organization-programmatic-access-grant-request.md)

