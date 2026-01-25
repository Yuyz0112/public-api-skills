# GET /orgs/{org}/personal-access-tokens/{pat_id}/repositories

**Resource:** [orgs](../resources/orgs.md)
**List repositories a fine-grained personal access token has access to**
**Operation ID:** `orgs/list-pat-grant-repositories`

Lists the repositories a fine-grained personal access token has access to.

Only GitHub Apps can use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pat_id` | path | integer | Yes | Unique identifier of the fine-grained personal access token. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

