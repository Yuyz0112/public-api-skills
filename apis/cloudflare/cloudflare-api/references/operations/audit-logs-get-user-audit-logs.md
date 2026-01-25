# GET /user/audit_logs

**Resource:** [Audit Logs](../resources/Audit-Logs.md)
**Get user audit logs**
**Operation ID:** `audit-logs-get-user-audit-logs`

Gets a list of audit logs for a user account. Can be filtered by who made the change, on which zone, and the timeframe of the change.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
| 200 | Get user audit logs response |
| 4XX | Get user audit logs response failure |

**Success Response Schema:**

[aaa_audit_logs_response_collection](../schemas/aaa/aaa-audit-logs-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
