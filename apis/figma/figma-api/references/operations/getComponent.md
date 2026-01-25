# GET /v1/components/{key}

**Resource:** [Components](../resources/Components.md)
**Get component**
**Operation ID:** `getComponent`

Get metadata on a component by key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The unique identifier of the component. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: library_assets:read, files:read
