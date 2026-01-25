# GET /accounts/{account_id}/builds/builds

**Resource:** [Builds](../resources/Builds.md)
**Get builds by version IDs**
**Operation ID:** `getBuildsByVersionIds`

Retrieve builds for specific version IDs

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `version_ids` | query | string | Yes | Comma-separated list of version UUIDs (max 20) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Builds retrieved successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
