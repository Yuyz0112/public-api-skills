# GET /licenses

**Resource:** [licenses](../resources/licenses.md)
**Get all commonly used licenses**
**Operation ID:** `licenses/get-all-commonly-used`

Lists the most commonly used licenses on GitHub. For more information, see "[Licensing a repository ](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `featured` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

**Success Response Schema:**

Array of [license-simple](../schemas/license-simple/license-simple.md)

