# POST /zones/{zone_id}/origin_tls_client_auth

**Resource:** [Zone-Level Authenticated Origin Pulls](../resources/Zone-Level-Authenticated-Origin-Pulls.md)
**Upload Certificate**
**Operation ID:** `zone-level-authenticated-origin-pulls-upload-certificate`

Upload your own certificate you want Cloudflare to use for edge-to-origin communication to override the shared certificate. Please note that it is important to keep only one certificate active. Also, make sure to enable zone-level authenticated origin pulls by making a PUT call to settings endpoint to see the uploaded certificate in use.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload Certificate response |
| 4XX | Upload Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_components-schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-components-schemas-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
