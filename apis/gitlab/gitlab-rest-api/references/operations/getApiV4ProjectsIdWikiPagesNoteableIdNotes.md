# GET /api/v4/projects/{id}/wiki_pages/{noteable_id}/notes

**Resource:** [Notes](../resources/Notes.md)
**Get a list of wiki page meta notes**
**Operation ID:** `getApiV4ProjectsIdWikiPagesNoteableIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the noteable |
| `order_by` | query | enum: created_at, updated_at | No | Return notes ordered by `created_at` or `updated_at` fields. |
| `sort` | query | enum: asc, desc | No | Return notes sorted in `asc` or `desc` order. |
| `activity_filter` | query | enum: all_notes, only_comments, only_activity | No | The type of notables which are returned. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

