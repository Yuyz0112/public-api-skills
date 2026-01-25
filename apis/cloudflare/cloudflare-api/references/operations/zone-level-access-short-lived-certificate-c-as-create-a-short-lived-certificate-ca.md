# POST /zones/{zone_id}/access/apps/{app_id}/ca

**Resource:** [Zone-Level Access short-lived certificate CAs](../resources/Zone-Level-Access-short-lived-certificate-CAs.md)
**Create a short-lived certificate CA**
**Operation ID:** `zone-level-access-short-lived-certificate-c-as-create-a-short-lived-certificate-ca`

Generates a new short-lived certificate CA and public key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a short-lived certificate CA response |
| 4XX | Create a short-lived certificate CA response failure |

**Success Response Schema:**

[access_ca_components-schemas-single_response-2](../schemas/access/access-ca-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
