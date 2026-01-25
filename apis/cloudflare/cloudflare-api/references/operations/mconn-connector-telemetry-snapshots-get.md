# GET /accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots/{snapshot_t}

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Get Snapshot**
**Operation ID:** `mconn-connector-telemetry-snapshots-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | string | Yes |  |
| `snapshot_t` | path | number | Yes |  |

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

[mconn_customer_snapshot_get_success](../schemas/mconn/mconn-customer-snapshot-get-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
