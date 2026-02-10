# GET /api/v4/groups/{id}/approval_rules

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Get all group approval rules**
**Operation ID:** `getApiV4GroupsIdApprovalRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupApprovalRule](../schemas/APIEntitiesGroupApprovalRule/APIEntitiesGroupApprovalRule.md)

