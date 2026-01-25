# POST /certificates

**Resource:** [Origin CA](../resources/Origin-CA.md)
**Create Certificate**
**Operation ID:** `origin-ca-create-certificate`

Create an Origin CA certificate. You can use an Origin CA Key as your User Service Key or an API token when calling this endpoint ([see above](#requests)).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Certificate response |
| 4XX | Create Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-schemas-certificate-response-single.md)

## Security

- **user_service_key**
- **api_token**
