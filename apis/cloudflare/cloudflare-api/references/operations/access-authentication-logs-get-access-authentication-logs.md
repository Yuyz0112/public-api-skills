# GET /accounts/{account_id}/access/logs/access_requests

**Resource:** [Access authentication logs](../resources/Access-authentication-logs.md)
**Get Access authentication logs**
**Operation ID:** `access-authentication-logs-get-access-authentication-logs`

Gets a list of Access authentication audit logs for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `limit` | query | integer | No | The maximum number of log entries to retrieve. |
| `direction` | query | enum: desc, asc | No | The chronological sorting order for the logs. |
| `since` | query | string (date-time) | No | The earliest event timestamp to query. |
| `until` | query | string (date-time) | No | The latest event timestamp to query. |
| `per_page` | query | integer | No |  |
| `email` | query | access_components-schemas-email | No | Filter by user email. Defaults to substring matching. To force exact matching, set `email_exact=true`.
Example (default): `email=@example.com` returns all events with that domain.
Example (exact): `email=user@example.com&email_exact=true` returns only that user.
 |
| `email_exact` | query | boolean | No | When true, `email` is matched exactly instead of substring matching. |
| `user_id` | query | access_user_id | No | Filter by user UUID.
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Access authentication logs response |
| 4XX | Get Access authentication logs response failure |

**Success Response Schema:**

[access_access-requests_components-schemas-response_collection](../schemas/access/access-access-requests-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
