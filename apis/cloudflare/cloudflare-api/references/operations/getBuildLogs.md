# GET /accounts/{account_id}/builds/builds/{build_uuid}/logs

**Resource:** [Builds](../resources/Builds.md)
**Get build logs**
**Operation ID:** `getBuildLogs`

Retrieve logs for a specific build with cursor-based pagination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cursor` | query | string | No | Pagination cursor for log retrieval |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Build logs retrieved successfully |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
