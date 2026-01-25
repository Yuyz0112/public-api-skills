# PUT /accounts/{account_id}/challenges/widgets/{sitekey}

**Resource:** [Turnstile](../resources/Turnstile.md)
**Update a Turnstile Widget**
**Operation ID:** `accounts-turnstile-widget-update`

Update the configuration of a widget.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Turnstile Widget Response |
| 4XX | Update Turnstile Widget Response Error |

## Security

- **api_token**
- **api_email**
- **api_key**
