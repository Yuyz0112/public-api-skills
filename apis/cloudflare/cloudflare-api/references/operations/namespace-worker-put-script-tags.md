# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Put Script Tags**
**Operation ID:** `namespace-worker-put-script-tags`

Put script tags for a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_tags](../schemas/workers/workers-tags.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script tags. |
| 4XX | Fetch script tags failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
