# POST /api/v4/projects/{id}/labels/{subscribable_id}/unsubscribe

**Resource:** [Resource subscriptions](../resources/Resource-subscriptions.md)
**Unsubscribe from a resource**
**Operation ID:** `postApiV4ProjectsIdLabelsSubscribableIdUnsubscribe`

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

[APIEntitiesProjectLabel](../schemas/APIEntitiesProjectLabel/APIEntitiesProjectLabel.md)

