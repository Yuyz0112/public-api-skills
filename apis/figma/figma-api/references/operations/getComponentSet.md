# GET /v1/component_sets/{key}

**Resource:** [Component Sets](../resources/Component-Sets.md)
**Get component set**
**Operation ID:** `getComponentSet`

Get metadata on a published component set by key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The unique identifier of the component set. |

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
