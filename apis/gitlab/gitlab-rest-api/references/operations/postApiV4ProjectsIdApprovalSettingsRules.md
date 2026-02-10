# POST /api/v4/projects/{id}/approval_settings/rules

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Create new approval rule**
**Operation ID:** `postApiV4ProjectsIdApprovalSettingsRules`

Private API subject to change

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

[APIEntitiesProjectApprovalSettingRule](../schemas/APIEntitiesProjectApprovalSettingRule/APIEntitiesProjectApprovalSettingRule.md)

