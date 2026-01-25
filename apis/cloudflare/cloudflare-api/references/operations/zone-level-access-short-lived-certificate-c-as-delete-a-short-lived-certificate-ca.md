# DELETE /zones/{zone_id}/access/apps/{app_id}/ca

**Resource:** [Zone-Level Access short-lived certificate CAs](../resources/Zone-Level-Access-short-lived-certificate-CAs.md)
**Delete a short-lived certificate CA**
**Operation ID:** `zone-level-access-short-lived-certificate-c-as-delete-a-short-lived-certificate-ca`

Deletes a short-lived certificate CA.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete a short-lived certificate CA response |
| 4XX | Delete a short-lived certificate CA response failure |

## Security

- **api_email**
- **api_key**
