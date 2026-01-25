# GET /certificates/{certificate_id}

**Resource:** [Origin CA](../resources/Origin-CA.md)
**Get Certificate**
**Operation ID:** `origin-ca-get-certificate`

Get an existing Origin CA certificate by its serial number. You can use an Origin CA Key as your User Service Key or an API token when calling this endpoint ([see above](#requests)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Certificate response |
| 4XX | Get Certificate response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_schemas-certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-schemas-certificate-response-single.md)

## Security

- **user_service_key**
- **api_token**
