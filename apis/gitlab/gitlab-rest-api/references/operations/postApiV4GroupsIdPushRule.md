# POST /api/v4/groups/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Add a push rule to a group**
**Operation ID:** `postApiV4GroupsIdPushRule`

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
| 201 | Created |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesGroupPushRule](../schemas/APIEntitiesGroupPushRule/APIEntitiesGroupPushRule.md)

