# DELETE /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Delete dispatch namespace**
**Operation ID:** `namespace-worker-delete-namespace`

Delete a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a Workers for Platforms namespace. |
| 4XX | Failure to delete Workers for Platforms namespace. |

**Success Response Schema:**

[workers_api-response-null-result](../schemas/workers/workers-api-response-null-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
