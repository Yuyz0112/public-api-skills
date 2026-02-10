# GET /api/v4/projects/{id}/wikis/{slug}

**Resource:** [Wikis](../resources/Wikis.md)
**Get a wiki page**
**Operation ID:** `getApiV4ProjectsIdWikisSlug`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes | The slug of a wiki page |
| `version` | query | string | No | The version hash of a wiki page |
| `render_html` | query | boolean | No | Render content to HTML |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesWikiPage](../schemas/APIEntitiesWikiPage/APIEntitiesWikiPage.md)

