# GET /api/v4/pages/domains

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Get all pages domains**
**Operation ID:** `getApiV4PagesDomains`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain` | query | string | No | The domain of the GitLab Pages site to filter on. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesPagesDomainBasic](../schemas/APIEntitiesPagesDomainBasic/APIEntitiesPagesDomainBasic.md)

