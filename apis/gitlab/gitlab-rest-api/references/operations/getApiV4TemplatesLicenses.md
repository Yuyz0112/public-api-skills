# GET /api/v4/templates/licenses

**Resource:** [Templates](../resources/Templates.md)
**Get all license templates**
**Operation ID:** `getApiV4TemplatesLicenses`

This feature was introduced in GitLab 8.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `popular` | query | boolean | No | If passed, returns only popular licenses |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesLicense](../schemas/APIEntitiesLicense/APIEntitiesLicense.md)

