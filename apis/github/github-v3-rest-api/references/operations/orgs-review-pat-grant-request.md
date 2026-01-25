# POST /orgs/{org}/personal-access-token-requests/{pat_request_id}

**Resource:** [orgs](../resources/orgs.md)
**Review a request to access organization resources with a fine-grained personal access token**
**Operation ID:** `orgs/review-pat-grant-request`

Approves or denies a pending request to access organization resources via a fine-grained personal access token.

Only GitHub Apps can use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pat_request_id` | path | integer | Yes | Unique identifier of the request for access via fine-grained personal access token. |

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

