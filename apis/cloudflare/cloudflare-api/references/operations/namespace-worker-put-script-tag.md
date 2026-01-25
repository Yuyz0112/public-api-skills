# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags/{tag}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Put Script Tag**
**Operation ID:** `namespace-worker-put-script-tag`

Put a single tag on a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `tag` | path | workers_tag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Put script tag. |
| 4XX | Put script tag failure. |

**Success Response Schema:**

[workers_api-response-null-result](../schemas/workers/workers-api-response-null-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
