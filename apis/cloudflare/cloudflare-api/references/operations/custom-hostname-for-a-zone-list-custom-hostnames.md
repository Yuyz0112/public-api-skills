# GET /zones/{zone_id}/custom_hostnames

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**List Custom Hostnames**
**Operation ID:** `custom-hostname-for-a-zone-list-custom-hostnames`

List, search, sort, and filter all of your custom hostnames.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `hostname` | query | string | No |  |
| `id` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: ssl, ssl_status | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `ssl` | query | enum: 0, 1 | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Custom Hostnames response |
| 4XX | List Custom Hostnames response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_hostname_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-hostname-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
