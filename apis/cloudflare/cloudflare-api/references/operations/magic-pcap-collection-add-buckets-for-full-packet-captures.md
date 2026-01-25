# POST /accounts/{account_id}/pcaps/ownership

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Add buckets for full packet captures**
**Operation ID:** `magic-pcap-collection-add-buckets-for-full-packet-captures`

Adds an AWS or GCP bucket to use with full packet captures.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic-visibility-pcaps_pcaps_ownership_request](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-ownership-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add buckets for full packet captures response. |
| default | Add buckets for full packet captures response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_ownership_single_response](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-ownership-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
