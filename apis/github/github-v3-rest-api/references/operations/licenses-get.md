# GET /licenses/{license}

**Resource:** [licenses](../resources/licenses.md)
**Get a license**
**Operation ID:** `licenses/get`

Gets information about a specific license. For more information, see "[Licensing a repository ](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `license` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[license](../schemas/license/license.md)

