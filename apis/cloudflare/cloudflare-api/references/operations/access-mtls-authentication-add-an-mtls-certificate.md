# POST /accounts/{account_id}/access/certificates

**Resource:** [Access mTLS authentication](../resources/Access-mTLS-authentication.md)
**Add an mTLS certificate**
**Operation ID:** `access-mtls-authentication-add-an-mtls-certificate`

Adds a new mTLS root certificate to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an mTLS certificate response |
| 4XX | Add an mTLS certificate response failure |

**Success Response Schema:**

[access_certificates_components-schemas-single_response](../schemas/access/access-certificates-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
