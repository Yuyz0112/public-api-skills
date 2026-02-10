# POST /api/v4/groups/{id}/approval_rules

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Create new group approval rule**
**Operation ID:** `postApiV4GroupsIdApprovalRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupApprovalRule](../schemas/APIEntitiesGroupApprovalRule/APIEntitiesGroupApprovalRule.md)

