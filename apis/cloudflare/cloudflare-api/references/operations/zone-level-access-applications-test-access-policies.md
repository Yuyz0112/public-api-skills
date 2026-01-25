# GET /zones/{zone_id}/access/apps/{app_id}/user_policy_checks

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Test Access policies**
**Operation ID:** `zone-level-access-applications-test-access-policies`

Tests if a specific user has permission to access an application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Test Access policies response |
| 4XX | Test Access policies response failure |

**Success Response Schema:**

[access_schemas-policy_check_response](../schemas/access/access-schemas-policy-check-response.md)

## Security

- **api_email**
- **api_key**
