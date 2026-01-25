# GET /accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots/latest

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Get latest Snapshots**
**Operation ID:** `mconn-connector-telemetry-snapshots-listLatest`

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

[mconn_customer_snapshots_get_latest_success](../schemas/mconn/mconn-customer-snapshots-get-latest-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
