# POST /api/v4/projects/{id}/pages/domains

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Create a new pages domain**
**Operation ID:** `postApiV4ProjectsIdPagesDomains`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPagesDomain](../schemas/APIEntitiesPagesDomain/APIEntitiesPagesDomain.md)

