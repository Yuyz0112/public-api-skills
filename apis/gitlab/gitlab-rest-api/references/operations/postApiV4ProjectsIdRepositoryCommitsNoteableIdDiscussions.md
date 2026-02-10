# POST /api/v4/projects/{id}/repository/commits/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Create a new commit discussion**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommitsNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | string | Yes | The ID of the commit |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

