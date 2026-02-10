# POST /api/v4/groups/{id}/labels/{subscribable_id}/subscribe

**Resource:** [Resource subscriptions](../resources/Resource-subscriptions.md)
**Subscribe to a resource**
**Operation ID:** `postApiV4GroupsIdLabelsSubscribableIdSubscribe`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `subscribable_id` | path | string | Yes | The ID of a resource |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupLabel](../schemas/APIEntitiesGroupLabel/APIEntitiesGroupLabel.md)

