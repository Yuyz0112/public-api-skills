# GET /zones/{zone_id}/custom_hostnames/{custom_hostname_id}

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Custom Hostname Details**
**Operation ID:** `custom-hostname-for-a-zone-custom-hostname-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_hostname_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Custom Hostname Details response |
| 4XX | Custom Hostname Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_hostname_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-hostname-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
