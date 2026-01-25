# POST /zones/{zone_id}/dns_records

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Create DNS Record**
**Operation ID:** `dns-records-for-a-zone-create-dns-record`

Create a new DNS record for a zone.

Notes:
- A/AAAA records cannot exist on the same name as CNAME records.
- NS records cannot exist on the same name as any other record type.
- Domain names are always represented in Punycode, even if Unicode
  characters were used when creating the record.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-records_dns-record-post](../schemas/dns-records/dns-records-dns-record-post.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create DNS Record response |
| 4XX | Create DNS Record response failure |

**Success Response Schema:**

[dns-records_dns_response_single](../schemas/dns-records/dns-records-dns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
