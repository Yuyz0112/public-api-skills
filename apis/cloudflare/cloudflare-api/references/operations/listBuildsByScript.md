# GET /accounts/{account_id}/builds/workers/{external_script_id}/builds

**Resource:** [Workers](../resources/Workers.md)
**List builds by script**
**Operation ID:** `listBuildsByScript`

Get all builds for a specific worker script with pagination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `external_script_id` | path | string | Yes | External script identifier |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Builds retrieved successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
