# DELETE /accounts/{account_id}/gateway/certificates/{certificate_id}

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**Delete Zero Trust certificate**
**Operation ID:** `zero-trust-certificates-delete-zero-trust-certificate`

Delete a gateway-managed Zero Trust certificate. You must deactivate the certificate from the edge (inactive) before deleting it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | zero-trust-gateway_uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deletes Zero Trust certificate response. |
| 4XX | Deletes Zero Trust certificate response failure. |

**Success Response Schema:**

[zero-trust-gateway_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
