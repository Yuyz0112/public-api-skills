# GET /api/v4/groups/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Get group push rule**
**Operation ID:** `getApiV4GroupsIdPushRule`

This feature was introduced in GitLab 13.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesGroupPushRule](../schemas/APIEntitiesGroupPushRule/APIEntitiesGroupPushRule.md)

