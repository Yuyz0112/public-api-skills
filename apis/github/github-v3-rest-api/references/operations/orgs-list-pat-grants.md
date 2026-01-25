# GET /orgs/{org}/personal-access-tokens

**Resource:** [orgs](../resources/orgs.md)
**List fine-grained personal access tokens with access to organization resources**
**Operation ID:** `orgs/list-pat-grants`

Lists approved fine-grained personal access tokens owned by organization members that can access organization resources.

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

Array of [organization-programmatic-access-grant](../schemas/organization-programmatic-access-grant/organization-programmatic-access-grant.md)

