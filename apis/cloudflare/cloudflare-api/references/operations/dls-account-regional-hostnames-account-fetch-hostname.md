# GET /zones/{zone_id}/addressing/regional_hostnames/{hostname}

**Resource:** [DLS Regional Services](../resources/DLS-Regional-Services.md)
**Fetch Regional Hostname**
**Operation ID:** `dls-account-regional-hostnames-account-fetch-hostname`

Fetch the configuration for a specific Regional Hostname, within a zone.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch hostname response |
| 4XX | Failure to fetch hostname |

## Security

- **api_email**
- **api_key**
- **api_token**
