# GET /api/v4/groups/{id}/related_epic_links

**Resource:** [Epics](../resources/Epics.md)
**Get related epics within the group and hierarchy**
**Operation ID:** `getApiV4GroupsIdRelatedEpicLinks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |
| `updated_before` | query | string (date-time) | No | Return related epic links updated before the specified time |
| `updated_after` | query | string (date-time) | No | Return related epic links updated after the specified time |
| `created_before` | query | string (date-time) | No | Return related epic links created before the specified time |
| `created_after` | query | string (date-time) | No | Return related epic links created after the specified time |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesRelatedEpic](../schemas/APIEntitiesRelatedEpic/APIEntitiesRelatedEpic.md)

