# PATCH /zones/{zone_id}/custom_hostnames/{custom_hostname_id}

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Edit Custom Hostname**
**Operation ID:** `custom-hostname-for-a-zone-edit-custom-hostname`

Modify SSL configuration for a custom hostname. When sent with SSL config that matches existing config, used to indicate that hostname should pass domain control validation (DCV). Can also be used to change validation type, e.g., from 'http' to 'email'. Bundle an existing certificate with another certificate by using the "custom_cert_bundle" field. The bundling process supports combining certificates as long as the following condition is met. One certificate must use the RSA algorithm, and the other must use the ECDSA algorithm.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_hostname_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Custom Hostname response |
| 4XX | Edit Custom Hostname response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_hostname_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-hostname-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
