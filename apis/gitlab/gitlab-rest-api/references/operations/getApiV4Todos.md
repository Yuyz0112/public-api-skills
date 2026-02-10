# GET /api/v4/todos

**Resource:** [To-dos](../resources/To-dos.md)
**Get a list of to-do items**
**Operation ID:** `getApiV4Todos`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `action` | query | enum: assigned, review_requested, mentioned... | No | The action to be filtered |
| `author_id` | query | integer | No | The ID of an author |
| `project_id` | query | integer | No | The ID of a project |
| `group_id` | query | integer | No | The ID of a group |
| `state` | query | enum: pending, done | No | The state of the to-do item |
| `type` | query | enum: Commit, Issue, WorkItem... | No | The type of to-do item |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTodo](../schemas/APIEntitiesTodo/APIEntitiesTodo.md)

