# GET /v1/files/{file_key}/styles

**Resource:** [Styles](../resources/Styles.md)
**Get file styles**
**Operation ID:** `getFileStyles`

Get a list of published styles within a file library.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to list styles from. This must be a main file key, not a branch key, as it is not possible to publish from branches. |

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
- **OAuth2**: library_content:read, files:read
