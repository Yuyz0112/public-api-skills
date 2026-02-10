# GET /api/v4/projects/{id}/pages/domains

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Get all pages domains**
**Operation ID:** `getApiV4ProjectsIdPagesDomains`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesPagesDomain](../schemas/APIEntitiesPagesDomain/APIEntitiesPagesDomain.md)

