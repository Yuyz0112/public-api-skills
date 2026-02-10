# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/todo

**Resource:** [To-dos](../resources/To-dos.md)
**Create a to-do item on an issuable**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidTodo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `merge_request_iid` | path | integer | Yes | The internal ID of an issuable |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesTodo](../schemas/APIEntitiesTodo/APIEntitiesTodo.md)

