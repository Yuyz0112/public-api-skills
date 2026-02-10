# GET /api/v4/projects/{id}/repository/commits/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Get a list of commit discussions**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | string | Yes | The ID of the commit |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

