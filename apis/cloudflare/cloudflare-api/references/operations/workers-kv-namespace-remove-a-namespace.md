# DELETE /accounts/{account_id}/storage/kv/namespaces/{namespace_id}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Remove a Namespace**
**Operation ID:** `workers-kv-namespace-remove-a-namespace`

Deletes the namespace corresponding to the given ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove a Namespace response. |
| 4XX | Remove a Namespace response failure. |

**Success Response Schema:**

[workers-kv_api-response-common-no-result](../schemas/workers-kv/workers-kv-api-response-common-no-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
