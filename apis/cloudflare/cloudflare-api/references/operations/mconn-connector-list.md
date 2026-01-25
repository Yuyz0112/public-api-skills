# GET /accounts/{account_id}/magic/connectors

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**List Connectors**
**Operation ID:** `mconn-connector-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[mconn_customer_connector_list_response](../schemas/mconn/mconn-customer-connector-list-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
