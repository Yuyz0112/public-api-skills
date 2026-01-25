# GET /accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**List Snapshots**
**Operation ID:** `mconn-connector-telemetry-snapshots-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | string | Yes |  |
| `from` | query | number | Yes |  |
| `to` | query | number | Yes |  |
| `limit` | query | number | No |  |
| `cursor` | query | string | No |  |

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

[mconn_customer_snapshots_get_success](../schemas/mconn/mconn-customer-snapshots-get-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
