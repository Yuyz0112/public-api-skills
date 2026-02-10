# GET /api/v4/projects/{id}/merge_requests/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Get a list of merge request discussions**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the merge request |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

