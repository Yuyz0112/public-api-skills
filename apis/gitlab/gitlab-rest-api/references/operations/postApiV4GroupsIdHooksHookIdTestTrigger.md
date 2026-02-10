# POST /api/v4/groups/{id}/hooks/{hook_id}/test/{trigger}

**Resource:** [Hooks](../resources/Hooks.md)
**Triggers a hook test**
**Operation ID:** `postApiV4GroupsIdHooksHookIdTestTrigger`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `trigger` | path | enum: confidential_issues_events, confidential_note_events, deployment_events... | Yes | The type of trigger hook |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 404 | Not found |
| 422 | Unprocessable entity |
| 429 | Too many requests |

