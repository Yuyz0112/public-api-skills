# PATCH /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/settings

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Patch Script Settings**
**Operation ID:** `namespace-worker-patch-script-settings`

Patch script metadata, such as bindings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch script settings. |
| 4XX | Patch script settings failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
