# POST /zones/{zone_id}/dns_records/batch

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Batch DNS Records**
**Operation ID:** `dns-records-for-a-zone-batch-dns-records`

Send a Batch of DNS Record API calls to be executed together.

Notes:
- Although Cloudflare will execute the batched operations in a single database transaction, Cloudflare's distributed KV store must treat each record change as a single key-value pair. This means that the propagation of changes is not atomic. See [the documentation](https://developers.cloudflare.com/dns/manage-dns-records/how-to/batch-record-changes/ "Batch DNS records") for more information.
- The operations you specify within the /batch request body are always executed in the following order:

    - Deletes
    - Patches
    - Puts
    - Posts


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-records_dns-request-batch-object](../schemas/dns-records/dns-records-dns-request-batch-object.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Batch DNS Records response |
| 4XX | Batch DNS Records response failure |

**Success Response Schema:**

[dns-records_dns_response_batch](../schemas/dns-records/dns-records-dns-response-batch.md)

## Security

- **api_token**
- **api_email**
- **api_key**
