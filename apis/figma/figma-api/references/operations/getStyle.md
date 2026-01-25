# GET /v1/styles/{key}

**Resource:** [Styles](../resources/Styles.md)
**Get style**
**Operation ID:** `getStyle`

Get metadata on a style by key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The unique identifier of the style. |

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
