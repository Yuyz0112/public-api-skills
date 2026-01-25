# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**List Scripts in Namespace**
**Operation ID:** `namespace-worker-list-scripts`

Fetch a list of scripts uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `tags` | query | string | No | Filter scripts by tags. Format: comma-separated list of tag:allowed pairs where allowed is 'yes' or 'no'. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List scripts in namespace response. |
| 4XX | List scripts in namespace response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
