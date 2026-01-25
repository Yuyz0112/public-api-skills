# GET /accounts/{account_id}/workers/scripts/{script_name}/versions

**Resource:** [Worker Versions](../resources/Worker-Versions.md)
**List Versions**
**Operation ID:** `worker-versions-list-versions`

List of Worker Versions. The first version in the list is the latest version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_schemas-script_name | Yes |  |
| `deployable` | query | boolean | No | Only return versions that can be used in a deployment. Ignores pagination. |
| `page` | query | integer | No | Current page. |
| `per_page` | query | integer | No | Items per-page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Versions response. |
| 4XX | List Versions response failure. |

**Success Response Schema:**

[workers_versions-list-response](../schemas/workers/workers-versions-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
