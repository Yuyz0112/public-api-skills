# GET /accounts/{account_id}/email/routing/addresses

**Resource:** [Email Routing destination addresses](../resources/Email-Routing-destination-addresses.md)
**List destination addresses**
**Operation ID:** `email-routing-destination-addresses-list-destination-addresses`

Lists existing destination addresses.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `verified` | query | enum: true, false | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List destination addresses response |

**Success Response Schema:**

[email_destination_addresses_response_collection](../schemas/email/email-destination-addresses-response-collection.md)

## Security

- **api_email**
- **api_key**
