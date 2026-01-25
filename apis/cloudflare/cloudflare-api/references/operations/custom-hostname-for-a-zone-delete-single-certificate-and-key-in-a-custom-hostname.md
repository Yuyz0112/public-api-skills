# DELETE /zones/{zone_id}/custom_hostnames/{custom_hostname_id}/certificate_pack/{certificate_pack_id}/certificates/{certificate_id}

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Delete Single Certificate And Key For Custom Hostname**
**Operation ID:** `custom-hostname-for-a-zone-delete_single_certificate_and_key_in_a_custom_hostname`

Delete a single custom certificate from a certificate pack that contains two bundled certificates. Deletion is subject to the following constraints. You cannot delete a certificate if it is the only remaining certificate in the pack. At least one certificate must remain in the pack.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_hostname_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `certificate_pack_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete Single Certificate and Key In a Custom Hostname response |
| 4XX | Delete Single Certificate and Key In a Custom Hostname response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
