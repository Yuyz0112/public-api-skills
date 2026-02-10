# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/participants

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get single merge request participants**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidParticipants`

Get a list of merge request participants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesUserBasic](../schemas/APIEntitiesUserBasic/APIEntitiesUserBasic.md)

