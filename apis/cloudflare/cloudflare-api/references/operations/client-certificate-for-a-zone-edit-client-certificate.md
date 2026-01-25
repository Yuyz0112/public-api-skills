# PATCH /zones/{zone_id}/client_certificates/{client_certificate_id}

**Resource:** [API Shield Client Certificates for a Zone](../resources/API-Shield-Client-Certificates-for-a-Zone.md)
**Reactivate Client Certificate**
**Operation ID:** `client-certificate-for-a-zone-edit-client-certificate`

If a API Shield mTLS Client Certificate is in a pending_revocation state, you may reactivate it with this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `client_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Reactivate Client Certificate Response |
| 4XX | Reactivate Client Certificate Response Failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_client_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-client-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
