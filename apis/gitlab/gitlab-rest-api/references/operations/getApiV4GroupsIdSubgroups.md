# GET /api/v4/groups/{id}/subgroups

**Resource:** [Groups](../resources/Groups.md)
**Get a list of subgroups in this group.**
**Operation ID:** `getApiV4GroupsIdSubgroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `statistics` | query | boolean | No | Include project statistics |
| `archived` | query | boolean | No | Limit by archived status |
| `skip_groups` | query | any | No | Array of group ids to exclude from list |
| `all_available` | query | boolean | No | When `true`, returns all accessible groups. When `false`, returns only groups where the user is a member. |
| `visibility` | query | enum: private, internal, public | No | Limit by visibility |
| `search` | query | string | No | Search for a specific group |
| `owned` | query | boolean | No | Limit by owned by authenticated user |
| `order_by` | query | enum: name, path, id... | No | Order by name, path, id or similarity if searching |
| `sort` | query | enum: asc, desc | No | Sort by asc (ascending) or desc (descending) |
| `min_access_level` | query | enum: 10, 15, 20... | No | Minimum access level of authenticated user |
| `top_level_only` | query | boolean | No | Only include top-level groups |
| `marked_for_deletion_on` | query | string (date) | No | Return groups that are marked for deletion on this date |
| `active` | query | boolean | No | Limit by groups that are not archived and not marked for deletion |
| `repository_storage` | query | string | No | Filter by repository storage used by the group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

