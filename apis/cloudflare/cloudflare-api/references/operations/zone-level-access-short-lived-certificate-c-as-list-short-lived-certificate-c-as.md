# GET /zones/{zone_id}/access/apps/ca

**Resource:** [Zone-Level Access short-lived certificate CAs](../resources/Zone-Level-Access-short-lived-certificate-CAs.md)
**List short-lived certificate CAs**
**Operation ID:** `zone-level-access-short-lived-certificate-c-as-list-short-lived-certificate-c-as`

Lists short-lived certificate CAs and their public keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List short-lived certificate CAs response |
| 4XX | List short-lived certificate CAs response failure |

**Success Response Schema:**

[access_ca_components-schemas-response_collection-2](../schemas/access/access-ca-components-schemas-response-collection-2.md)

## Security

- **api_email**
- **api_key**
