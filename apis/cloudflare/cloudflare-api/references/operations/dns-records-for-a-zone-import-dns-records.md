# POST /zones/{zone_id}/dns_records/import

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Import DNS Records**
**Operation ID:** `dns-records-for-a-zone-import-dns-records`

You can upload your [BIND config](https://en.wikipedia.org/wiki/Zone_file "Zone file") through this endpoint. It assumes that cURL is called from a location with bind_config.txt (valid BIND config) present.

See [the documentation](https://developers.cloudflare.com/dns/manage-dns-records/how-to/import-and-export/ "Import and export records") for more information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Import DNS Records response |
| 4XX | Import DNS Records response failure |

**Success Response Schema:**

[dns-records_dns_response_import_scan](../schemas/dns-records/dns-records-dns-response-import-scan.md)

## Security

- **api_token**
- **api_email**
- **api_key**
