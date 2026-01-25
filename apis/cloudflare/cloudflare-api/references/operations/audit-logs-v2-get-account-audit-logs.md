# GET /accounts/{account_id}/logs/audit

**Resource:** [Audit Logs](../resources/Audit-Logs.md)
**Get account audit logs (Version 2, Beta release)**
**Operation ID:** `audit-logs-v2-get-account-audit-logs`

Gets a list of audit logs for an account. <br />  <br /> This is the beta release of Audit Logs Version 2. Since this is a beta version, there may be gaps or missing entries in the available audit logs. Be aware of the following limitations.  <br /> <ul> <li>Audit logs are available only for the past 30 days. <br /></li> <li>Error handling is not yet implemented.  <br /> </li> </ul>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `account_name` | query | string[] | No |  |
| `action_result` | query | string[] | No |  |
| `action_type` | query | string[] | No |  |
| `actor_context` | query | string[] | No |  |
| `actor_email` | query | string[] | No |  |
| `actor_id` | query | string[] | No |  |
| `actor_ip_address` | query | string[] | No |  |
| `actor_token_id` | query | string[] | No |  |
| `actor_token_name` | query | string[] | No |  |
| `actor_type` | query | string[] | No |  |
| `audit_log_id` | query | string[] | No |  |
| `id` | query | string[] | No |  |
| `raw_cf_ray_id` | query | string[] | No |  |
| `raw_method` | query | string[] | No |  |
| `raw_status_code` | query | integer[] | No |  |
| `raw_uri` | query | string[] | No |  |
| `resource_id` | query | string[] | No |  |
| `resource_product` | query | string[] | No |  |
| `resource_type` | query | string[] | No |  |
| `resource_scope` | query | string[] | No |  |
| `zone_id` | query | string[] | No |  |
| `zone_name` | query | string[] | No |  |
| `account_name.not` | query | string[] | No |  |
| `action_result.not` | query | string[] | No |  |
| `action_type.not` | query | string[] | No |  |
| `actor_context.not` | query | string[] | No |  |
| `actor_email.not` | query | string[] | No |  |
| `actor_id.not` | query | string[] | No |  |
| `actor_ip_address.not` | query | string[] | No |  |
| `actor_token_id.not` | query | string[] | No |  |
| `actor_token_name.not` | query | string[] | No |  |
| `actor_type.not` | query | string[] | No |  |
| `audit_log_id.not` | query | string[] | No |  |
| `id.not` | query | string[] | No |  |
| `raw_cf_ray_id.not` | query | string[] | No |  |
| `raw_method.not` | query | string[] | No |  |
| `raw_status_code.not` | query | integer[] | No |  |
| `raw_uri.not` | query | string[] | No |  |
| `resource_id.not` | query | string[] | No |  |
| `resource_product.not` | query | string[] | No |  |
| `resource_type.not` | query | string[] | No |  |
| `resource_scope.not` | query | string[] | No |  |
| `zone_id.not` | query | string[] | No |  |
| `zone_name.not` | query | string[] | No |  |
| `since` | query | string (date) | Yes | Limits the returned results to logs newer than the specified date. This can be a date string 2019-04-30 (interpreted in UTC) or an absolute timestamp that conforms to RFC3339. |
| `before` | query | string (date) | Yes | Limits the returned results to logs older than the specified date. This can be a date string 2019-04-30 (interpreted in UTC) or an absolute timestamp that conforms to RFC3339. |
| `direction` | query | enum: desc, asc | No |  |
| `limit` | query | number | No |  |
| `cursor` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get account audit logs successful response |
| 4XX | Get account audit logs failed response |

**Success Response Schema:**

[aaa_audit-logs-v2-response-collection](../schemas/aaa/aaa-audit-logs-v2-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
