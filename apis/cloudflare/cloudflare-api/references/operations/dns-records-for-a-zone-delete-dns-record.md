# DELETE /zones/{zone_id}/dns_records/{dns_record_id}

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Delete DNS Record**
**Operation ID:** `dns-records-for-a-zone-delete-dns-record`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_record_id` | path | dns-records_identifier | Yes |  |
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete DNS Record response |
| 4XX | Delete DNS Record response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
