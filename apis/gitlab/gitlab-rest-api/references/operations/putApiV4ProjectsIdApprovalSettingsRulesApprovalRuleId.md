# PUT /api/v4/projects/{id}/approval_settings/rules/{approval_rule_id}

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Update approval rule**
**Operation ID:** `putApiV4ProjectsIdApprovalSettingsRulesApprovalRuleId`

Private API subject to change

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `approval_rule_id` | path | integer | Yes | The ID of an approval_rule |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectApprovalSettingRule](../schemas/APIEntitiesProjectApprovalSettingRule/APIEntitiesProjectApprovalSettingRule.md)

