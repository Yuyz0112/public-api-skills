# POST /api/v4/projects/{id}/issues/{subscribable_id}/subscribe

**Resource:** [Resource subscriptions](../resources/Resource-subscriptions.md)
**Subscribe to a resource**
**Operation ID:** `postApiV4ProjectsIdIssuesSubscribableIdSubscribe`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `subscribable_id` | path | string | Yes | The ID of a resource |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesIssue](../schemas/APIEntitiesIssue/APIEntitiesIssue.md)

