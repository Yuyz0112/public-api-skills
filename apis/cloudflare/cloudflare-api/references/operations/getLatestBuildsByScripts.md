# GET /accounts/{account_id}/builds/builds/latest

**Resource:** [Builds](../resources/Builds.md)
**Get latest builds by script IDs**
**Operation ID:** `getLatestBuildsByScripts`

Retrieve the most recent builds for multiple worker scripts

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `external_script_ids` | query | string | Yes | Comma-separated list of external script IDs (max 20) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Latest builds retrieved successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
