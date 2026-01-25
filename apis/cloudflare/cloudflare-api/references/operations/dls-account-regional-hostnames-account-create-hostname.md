# POST /zones/{zone_id}/addressing/regional_hostnames

**Resource:** [DLS Regional Services](../resources/DLS-Regional-Services.md)
**Create Regional Hostname**
**Operation ID:** `dls-account-regional-hostnames-account-create-hostname`

Create a new Regional Hostname entry. Cloudflare will only use data centers that are physically located within the chosen region to decrypt and service HTTPS traffic. Learn more about [Regional Services](https://developers.cloudflare.com/data-localization/regional-services/get-started/).

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create hostname response |
| 4XX | Failure to create hostname |

## Security

- **api_email**
- **api_key**
- **api_token**
