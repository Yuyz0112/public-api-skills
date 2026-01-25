# GET /accounts/{account_id}/pcaps/ownership

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**List PCAPs Bucket Ownership**
**Operation ID:** `magic-pcap-collection-list-pca-ps-bucket-ownership`

List all buckets configured for use with PCAPs API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List PCAPs Bucket Ownership response. |
| default | List PCAPs Bucket Ownership response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_ownership_collection](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-ownership-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
