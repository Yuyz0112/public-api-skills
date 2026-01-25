# DELETE /accounts/{account_id}/magic/connectors/{connector_id}

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Remove a connector from your account**
**Operation ID:** `mconn-connector-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | mconn_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

**Success Response Schema:**

[mconn_customer_connector_delete_response](../schemas/mconn/mconn-customer-connector-delete-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
