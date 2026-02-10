# GET /api/v4/groups/{id}/epics

**Resource:** [Epics](../resources/Epics.md)
**Get epics for the group**
**Operation ID:** `getApiV4GroupsIdEpics`

Gets all epics of the requested group and its subgroups

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `order_by` | query | enum: created_at, updated_at, title | No | Return epics ordered by `created_at`, `updated_at` or `title` fields. |
| `sort` | query | enum: asc, desc | No | Return epics sorted in `asc` or `desc` order. |
| `search` | query | string | No | Search epics for text present in the title or description |
| `state` | query | enum: opened, closed, all | No | Return opened, closed, or all epics |
| `author_id` | query | integer | No | Return epics which are authored by the user with the given ID |
| `author_username` | query | string | No | Return epics which are authored by the given username |
| `labels` | query | any | No | Comma-separated list of label names |
| `with_labels_details` | query | boolean | No | Return titles of labels and other details |
| `created_after` | query | string (date-time) | No | Return epics created after the specified time |
| `created_before` | query | string (date-time) | No | Return epics created before the specified time |
| `updated_after` | query | string (date-time) | No | Return epics updated after the specified time |
| `updated_before` | query | string (date-time) | No | Return epics updated before the specified time |
| `include_ancestor_groups` | query | boolean | No | Include epics from ancestor groups |
| `include_descendant_groups` | query | boolean | No | Include epics from descendant groups |
| `my_reaction_emoji` | query | string | No | Return epics reacted by the authenticated user by the given emoji |
| `confidential` | query | boolean | No | Return epics with given confidentiality |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `not` | query | object | No | Object that contains filters |
| `not[labels]` | query | any | No | Comma-separated list of label names |
| `not[author_id]` | query | integer | No | Return epics which are not authored by the user with the given ID |
| `not[author_username]` | query | string | No | Return epics which are not authored by the given username |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

