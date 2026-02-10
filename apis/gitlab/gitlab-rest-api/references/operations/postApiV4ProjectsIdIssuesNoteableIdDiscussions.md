# POST /api/v4/projects/{id}/issues/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Create a new issue discussion**
**Operation ID:** `postApiV4ProjectsIdIssuesNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the issue |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

