# PATCH /accounts/{account_id}/magic/connectors/{connector_id}

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Edit Connector to update specific properties or Re-provision License Key**
**Operation ID:** `mconn-connector-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |
| `connector_id` | path | mconn_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mconn_customer_connector_update_request](../schemas/mconn/mconn-customer-connector-update-request.md)

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

[mconn_customer_connector_update_response](../schemas/mconn/mconn-customer-connector-update-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
