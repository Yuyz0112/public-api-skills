# POST /v1/sigma/saved_queries/{id}

**Resource:** [sigma](../resources/sigma.md)
**Update an existing Sigma Query**
**Operation ID:** `PostSigmaSavedQueriesId`

<p>Update an existing Sigma query that previously exists</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The `id` of the saved query to update. This should be a valid `id` that was previously created. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[sigma.sigma_api_query](../schemas/sigma-sigma/sigma-sigma-api-query.md)

