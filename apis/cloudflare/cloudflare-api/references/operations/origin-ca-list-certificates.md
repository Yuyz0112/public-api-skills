# GET /certificates

**Resource:** [Origin CA](../resources/Origin-CA.md)
**List Certificates**
**Operation ID:** `origin-ca-list-certificates`

List all existing Origin CA certificates for a given zone. You can use an Origin CA Key as your User Service Key or an API token when calling this endpoint ([see above](#requests)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | query | tls-certificates-and-hostnames_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Certificates response |
| 4XX | List Certificates response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_schemas-certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-schemas-certificate-response-collection.md)

## Security

- **user_service_key**
- **api_token**
