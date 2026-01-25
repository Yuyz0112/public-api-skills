# POST /accounts/{account_id}/magic/connectors

**Resource:** [Magic Connectors](../resources/Magic-Connectors.md)
**Add a connector to your account**
**Operation ID:** `mconn-connector-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mconn_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mconn_customer_connector_create_request](../schemas/mconn/mconn-customer-connector-create-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 409 | Conflict |
| 500 | Internal Server Error |

**Success Response Schema:**

[mconn_customer_connector_create_response](../schemas/mconn/mconn-customer-connector-create-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
