# GET /api/v4/projects/{id}/packages/cargo/config.json

**Resource:** [Packages](../resources/Packages.md)
**Get config.json**
**Operation ID:** `getApiV4ProjectsIdPackagesCargoConfigJson`

This will be used by cargo for further requests

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

