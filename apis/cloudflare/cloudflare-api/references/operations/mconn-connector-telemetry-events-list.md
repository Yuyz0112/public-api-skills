# GET /accounts/{account_id}/magic/connectors/{connector_id}/telemetry/events

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**List Events**
**Operation ID:** `mconn-connector-telemetry-events-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | string | Yes |  |
| `from` | query | number | Yes |  |
| `to` | query | number | Yes |  |
| `limit` | query | number | No |  |
| `cursor` | query | string | No |  |
| `k` | query | string | No | Filter by event kind |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 429 | Too Many Requests |
| 500 | Internal Server Error |

**Success Response Schema:**

[mconn_customer_events_get_success](../schemas/mconn/mconn-customer-events-get-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
