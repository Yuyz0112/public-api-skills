# GET /accounts/{account_id}/email/routing/addresses/{destination_address_identifier}

**Resource:** [Email Routing destination addresses](../resources/Email-Routing-destination-addresses.md)
**Get a destination address**
**Operation ID:** `email-routing-destination-addresses-get-a-destination-address`

Gets information for a specific destination email already created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `destination_address_identifier` | path | email_destination_address_identifier | Yes |  |
| `account_id` | path | email_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a destination address response |

**Success Response Schema:**

[email_destination_address_response_single](../schemas/email/email-destination-address-response-single.md)

## Security

- **api_email**
- **api_key**
