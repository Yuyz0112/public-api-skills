# GET /accounts/{account_id}/addressing/regional_hostnames/regions

**Resource:** [DLS Regional Services](../resources/DLS-Regional-Services.md)
**List Regions**
**Operation ID:** `dls-account-regional-hostnames-account-list-regions`

List all Regional Services regions available for use by this account.

## Responses

| Status | Description |
|--------|-------------|
| 200 | List regions response |
| 4XX | Failure to list regions |

## Security

- **api_email**
- **api_key**
- **api_token**
