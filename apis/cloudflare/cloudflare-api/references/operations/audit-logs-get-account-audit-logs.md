# GET /accounts/{account_id}/audit_logs

**Resource:** [Audit Logs](../resources/Audit-Logs.md)
**Get account audit logs**
**Operation ID:** `audit-logs-get-account-audit-logs`

Gets a list of audit logs for an account. Can be filtered by who made the change, on which zone, and the timeframe of the change.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_identifier | Yes |  |
| `id` | query | string | No |  |
| `export` | query | boolean | No |  |
| `action.type` | query | string | No |  |
| `actor.ip` | query | string | No |  |
| `actor.email` | query | string (email) | No |  |
| `since` | query | any | No |  |
| `before` | query | any | No |  |
| `zone.name` | query | string | No |  |
| `direction` | query | enum: desc, asc | No |  |
| `per_page` | query | number | No |  |
| `page` | query | number | No |  |
| `hide_user_logs` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get account audit logs response |
| 4XX | Get account audit logs response failure |

**Success Response Schema:**

[aaa_audit_logs_response_collection](../schemas/aaa/aaa-audit-logs-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
