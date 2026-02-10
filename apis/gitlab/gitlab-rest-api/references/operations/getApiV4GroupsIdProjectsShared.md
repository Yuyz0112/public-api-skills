# GET /api/v4/groups/{id}/projects/shared

**Resource:** [Groups](../resources/Groups.md)
**Get a list of shared projects in this group**
**Operation ID:** `getApiV4GroupsIdProjectsShared`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `archived` | query | boolean | No | Limit by archived status |
| `visibility` | query | enum: private, internal, public | No | Limit by visibility |
| `search` | query | string | No | Return list of authorized projects matching the search criteria |
| `order_by` | query | enum: id, name, path... | No | Return projects ordered by field |
| `sort` | query | enum: asc, desc | No | Return projects sorted in ascending and descending order |
| `simple` | query | boolean | No | Return only the ID, URL, name, and path of each project |
| `starred` | query | boolean | No | Limit by starred status |
| `with_issues_enabled` | query | boolean | No | Limit by enabled issues feature |
| `with_merge_requests_enabled` | query | boolean | No | Limit by enabled merge requests feature |
| `min_access_level` | query | enum: 10, 15, 20... | No | Limit by minimum access level of authenticated user on projects |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)

