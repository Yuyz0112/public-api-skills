# GET /zones/{zone_id}/ssl/certificate_packs

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**List Certificate Packs**
**Operation ID:** `certificate-packs-list-certificate-packs`

For a given zone, list all active certificate packs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `status` | query | enum: all | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Certificate Packs response |
| 4XX | List Certificate Packs response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_pack_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-pack-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
