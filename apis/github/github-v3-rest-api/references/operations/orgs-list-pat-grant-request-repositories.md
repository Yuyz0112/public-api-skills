# GET /orgs/{org}/personal-access-token-requests/{pat_request_id}/repositories

**Resource:** [orgs](../resources/orgs.md)
**List repositories requested to be accessed by a fine-grained personal access token**
**Operation ID:** `orgs/list-pat-grant-request-repositories`

Lists the repositories a fine-grained personal access token request is requesting access to.

Only GitHub Apps can use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pat_request_id` | path | integer | Yes | Unique identifier of the request for access via fine-grained personal access token. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

