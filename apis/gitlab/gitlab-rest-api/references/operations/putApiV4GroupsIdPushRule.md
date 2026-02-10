# PUT /api/v4/groups/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Edit push rule of a group**
**Operation ID:** `putApiV4GroupsIdPushRule`

This feature was introduced in GitLab 13.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesGroupPushRule](../schemas/APIEntitiesGroupPushRule/APIEntitiesGroupPushRule.md)

