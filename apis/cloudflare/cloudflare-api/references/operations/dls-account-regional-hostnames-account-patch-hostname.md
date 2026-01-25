# PATCH /zones/{zone_id}/addressing/regional_hostnames/{hostname}

**Resource:** [DLS Regional Services](../resources/DLS-Regional-Services.md)
**Update Regional Hostname**
**Operation ID:** `dls-account-regional-hostnames-account-patch-hostname`

Update the configuration for a specific Regional Hostname. Only the region_key of a hostname is mutable.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update hostname response |
| 4XX | Failure to update hostname |

## Security

- **api_email**
- **api_key**
- **api_token**
