# DELETE /zones/{zone_id}/custom_hostnames/{custom_hostname_id}

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Delete Custom Hostname (and any issued SSL certificates)**
**Operation ID:** `custom-hostname-for-a-zone-delete-custom-hostname-(-and-any-issued-ssl-certificates)`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_hostname_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Custom Hostname (and any issued SSL certificates) response |
| 4XX | Delete Custom Hostname (and any issued SSL certificates) response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
