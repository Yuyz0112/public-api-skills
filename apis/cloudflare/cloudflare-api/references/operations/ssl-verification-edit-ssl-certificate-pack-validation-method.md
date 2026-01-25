# PATCH /zones/{zone_id}/ssl/verification/{certificate_pack_id}

**Resource:** [SSL Verification](../resources/SSL-Verification.md)
**Edit SSL Certificate Pack Validation Method**
**Operation ID:** `ssl-verification-edit-ssl-certificate-pack-validation-method`

Edit SSL validation method for a certificate pack. A PATCH request will request an immediate validation check on any certificate, and return the updated status. If a validation method is provided, the validation will be immediately attempted using that method.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_pack_id` | path | tls-certificates-and-hostnames_cert_pack_uuid | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tls-certificates-and-hostnames_components-schemas-validation_method](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-components-schemas-validation-method.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit SSL Certificate Pack Validation Method response |
| 4XX | Edit SSL Certificate Pack Validation Method response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_ssl_validation_method_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-ssl-validation-method-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
