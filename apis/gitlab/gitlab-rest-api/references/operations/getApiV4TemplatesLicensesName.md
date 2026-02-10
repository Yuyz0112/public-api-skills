# GET /api/v4/templates/licenses/{name}

**Resource:** [Templates](../resources/Templates.md)
**Get a single license template**
**Operation ID:** `getApiV4TemplatesLicensesName`

This feature was introduced in GitLab 8.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | The name of the license template |
| `project` | query | string | No | The copyrighted project name |
| `fullname` | query | string | No | The full-name of the copyright holder |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesLicense](../schemas/APIEntitiesLicense/APIEntitiesLicense.md)

