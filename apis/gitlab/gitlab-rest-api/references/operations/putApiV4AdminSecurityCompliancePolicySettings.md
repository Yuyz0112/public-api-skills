# PUT /api/v4/admin/security/compliance_policy_settings

**Resource:** [Compliance policy settings](../resources/Compliance-policy-settings.md)
**Update security policy settings**
**Operation ID:** `putApiV4AdminSecurityCompliancePolicySettings`

Update the security policy settings

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 422 | 422 Unprocessable Entity |

**Success Response Schema:**

[APIEntitiesAdminSecurityPolicySetting](../schemas/APIEntitiesAdminSecurityPolicySetting/APIEntitiesAdminSecurityPolicySetting.md)

