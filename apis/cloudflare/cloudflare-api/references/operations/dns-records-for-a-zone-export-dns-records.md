# GET /zones/{zone_id}/dns_records/export

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Export DNS Records**
**Operation ID:** `dns-records-for-a-zone-export-dns-records`

You can export your [BIND config](https://en.wikipedia.org/wiki/Zone_file "Zone file") through this endpoint.

See [the documentation](https://developers.cloudflare.com/dns/manage-dns-records/how-to/import-and-export/ "Import and export records") for more information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Export DNS Records response |
| 4XX | Export DNS Records response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
