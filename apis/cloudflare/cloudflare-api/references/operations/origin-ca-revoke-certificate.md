# DELETE /certificates/{certificate_id}

**Resource:** [Origin CA](../resources/Origin-CA.md)
**Revoke Certificate**
**Operation ID:** `origin-ca-revoke-certificate`

Revoke an existing Origin CA certificate by its serial number. You can use an Origin CA Key as your User Service Key or an API token when calling this endpoint ([see above](#requests)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revoke Certificate response |
| 4XX | Revoke Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_revoke_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-revoke-response.md)

## Security

- **user_service_key**
- **api_token**
