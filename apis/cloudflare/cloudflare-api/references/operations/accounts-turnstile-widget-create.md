# POST /accounts/{account_id}/challenges/widgets

**Resource:** [Turnstile](../resources/Turnstile.md)
**Create a Turnstile Widget**
**Operation ID:** `accounts-turnstile-widget-create`

Lists challenge widgets.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Turnstile Widget Response |
| 4XX | Create Turnstile Widget Response Error |

## Security

- **api_token**
- **api_email**
- **api_key**
