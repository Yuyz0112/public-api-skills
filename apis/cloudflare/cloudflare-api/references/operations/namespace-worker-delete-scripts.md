# DELETE /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Delete Scripts in Namespace**
**Operation ID:** `namespace-worker-delete-scripts`

Delete multiple scripts from a Workers for Platforms namespace based on optional tag filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `tags` | query | string | No | Filter scripts by tags before deletion. Format: comma-separated list of tag:allowed pairs where allowed is 'yes' or 'no'. |
| `limit` | query | integer | No | Limit the number of scripts to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete scripts in namespace response. |
| 4XX | Delete scripts in namespace response failure. |

**Success Response Schema:**

[workers_namespace-script-delete-bulk-response](../schemas/workers/workers-namespace-script-delete-bulk-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
