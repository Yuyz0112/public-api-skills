# GET /zones/{zone_id}/client_certificates

**Resource:** [API Shield Client Certificates for a Zone](../resources/API-Shield-Client-Certificates-for-a-Zone.md)
**List Client Certificates**
**Operation ID:** `client-certificate-for-a-zone-list-client-certificates`

List all of your Zone's API Shield mTLS Client Certificates by Status and/or using Pagination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `status` | query | enum: all, active, pending_reactivation... | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Client Certificates Response |
| 4XX | List Client Certificates Response Failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_client_certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-client-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
