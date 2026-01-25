# GET /accounts/{account_id}/access/logs/scim/updates

**Resource:** [Access SCIM update logs](../resources/Access-SCIM-update-logs.md)
**List Access SCIM update logs**
**Operation ID:** `access-scim-update-logs-list-access-scim-update-logs`

Lists Access SCIM update logs that maintain a record of updates made to User and Group resources synced to Cloudflare via the System for Cross-domain Identity Management (SCIM).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `limit` | query | access_limit | No |  |
| `direction` | query | access_direction | No |  |
| `since` | query | access_since | No |  |
| `until` | query | access_until | No |  |
| `idp_id` | query | access_idp_id | Yes |  |
| `status` | query | access_requests-status | No |  |
| `resource_type` | query | access_resource_type | No |  |
| `request_method` | query | access_request_method | No |  |
| `resource_user_email` | query | access_resource_user_email | No |  |
| `resource_group_name` | query | access_resource_group_name | No |  |
| `cf_resource_id` | query | access_requests-cf_resource_id | No |  |
| `idp_resource_id` | query | access_requests-idp_resource_id | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Access SCIM update logs response |
| 4XX | Get Access SCIM update logs response failure |

**Success Response Schema:**

[access_scim_update_logs_response](../schemas/access/access-scim-update-logs-response.md)

## Security

- **api_email**
- **api_key**
