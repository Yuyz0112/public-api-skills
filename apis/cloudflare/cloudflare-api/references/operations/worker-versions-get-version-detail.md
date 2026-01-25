# GET /accounts/{account_id}/workers/scripts/{script_name}/versions/{version_id}

**Resource:** [Worker Versions](../resources/Worker-Versions.md)
**Get Version Detail**
**Operation ID:** `worker-versions-get-version-detail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_schemas-script_name | Yes |  |
| `version_id` | path | workers_version_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Version Detail response. |
| 4XX | Get Version Detail response failure. |

**Success Response Schema:**

[workers_versions-single-response](../schemas/workers/workers-versions-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
