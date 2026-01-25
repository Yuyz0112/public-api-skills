# PUT /zones/{zone_id}/custom_hostnames/{custom_hostname_id}/certificate_pack/{certificate_pack_id}/certificates/{certificate_id}

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Replace Custom Certificate and Custom Key In Custom Hostname**
**Operation ID:** `custom-hostname-for-a-zone-edit-custom-certificate-custom-hostname`

Replace a single custom certificate within a certificate pack that contains two bundled certificates. The replacement must adhere to the following constraints. You can only replace an RSA certificate with another RSA certificate or an ECDSA certificate with another ECDSA certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_hostname_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `certificate_pack_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tls-certificates-and-hostnames_custom_cert_and_key](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-cert-and-key.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Edit Custom Certificate In a Custom Hostname response |
| 4XX | Edit Custom Certificate In a Custom Hostname response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
