# GET /zones/{zone_id}/access/apps/{app_id}/ca

**Resource:** [Zone-Level Access short-lived certificate CAs](../resources/Zone-Level-Access-short-lived-certificate-CAs.md)
**Get a short-lived certificate CA**
**Operation ID:** `zone-level-access-short-lived-certificate-c-as-get-a-short-lived-certificate-ca`

Fetches a short-lived certificate CA and its public key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a short-lived certificate CA response |
| 4XX | Get a short-lived certificate CA response failure |

**Success Response Schema:**

[access_ca_components-schemas-single_response-2](../schemas/access/access-ca-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
