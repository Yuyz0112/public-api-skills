# GET /accounts/{account_id}/magic/connectors/{connector_id}/telemetry/events/latest

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Get latest Events**
**Operation ID:** `mconn-connector-telemetry-events-listLatest`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 429 | Too Many Requests |
| 500 | Internal Server Error |

**Success Response Schema:**

[mconn_customer_events_get_latest_success](../schemas/mconn/mconn-customer-events-get-latest-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
