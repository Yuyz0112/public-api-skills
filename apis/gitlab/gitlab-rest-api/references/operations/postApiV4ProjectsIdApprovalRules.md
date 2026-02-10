# POST /api/v4/projects/{id}/approval_rules

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Create new project approval rule**
**Operation ID:** `postApiV4ProjectsIdApprovalRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesProjectApprovalRule](../schemas/APIEntitiesProjectApprovalRule/APIEntitiesProjectApprovalRule.md)

