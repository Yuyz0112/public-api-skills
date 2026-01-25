# POST /accounts/{account_id}/email/routing/addresses

**Resource:** [Email Routing destination addresses](../resources/Email-Routing-destination-addresses.md)
**Create a destination address**
**Operation ID:** `email-routing-destination-addresses-create-a-destination-address`

Create a destination address to forward your emails to. Destination addresses need to be verified before they can be used.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email_create_destination_address_properties](../schemas/email/email-create-destination-address-properties.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a destination address response |

**Success Response Schema:**

[email_destination_address_response_single](../schemas/email/email-destination-address-response-single.md)

## Security

- **api_email**
- **api_key**
