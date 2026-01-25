# POST /accounts/{account_id}/challenges/widgets/{sitekey}/rotate_secret

**Resource:** [Turnstile](../resources/Turnstile.md)
**Rotate Secret for a Turnstile Widget**
**Operation ID:** `accounts-turnstile-widget-rotate-secret`

Generate a new secret key for this widget. If `invalidate_immediately`
is set to `false`, the previous secret remains valid for 2 hours.

Note that secrets cannot be rotated again during the grace period.


## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rotate Secret Response |
| 4XX | Rotate Secret Response Error |

## Security

- **api_token**
- **api_email**
- **api_key**
