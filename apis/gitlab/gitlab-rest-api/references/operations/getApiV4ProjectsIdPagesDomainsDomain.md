# GET /api/v4/projects/{id}/pages/domains/{domain}

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Get a single pages domain**
**Operation ID:** `getApiV4ProjectsIdPagesDomainsDomain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `domain` | path | string | Yes | The domain |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesPagesDomain](../schemas/APIEntitiesPagesDomain/APIEntitiesPagesDomain.md)

