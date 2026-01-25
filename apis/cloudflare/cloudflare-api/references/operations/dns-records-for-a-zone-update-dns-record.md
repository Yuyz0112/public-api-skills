# PUT /zones/{zone_id}/dns_records/{dns_record_id}

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Overwrite DNS Record**
**Operation ID:** `dns-records-for-a-zone-update-dns-record`

Overwrite an existing DNS record.

Notes:
- A/AAAA records cannot exist on the same name as CNAME records.
- NS records cannot exist on the same name as any other record type.
- Domain names are always represented in Punycode, even if Unicode
  characters were used when creating the record.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_record_id` | path | dns-records_identifier | Yes |  |
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-records_dns-record-post](../schemas/dns-records/dns-records-dns-record-post.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update DNS Record response |
| 4XX | Update DNS Record response failure |

**Success Response Schema:**

[dns-records_dns_response_single](../schemas/dns-records/dns-records-dns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
