# POST /accounts/{account_id}/pcaps/ownership/validate

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Validate buckets for full packet captures**
**Operation ID:** `magic-pcap-collection-validate-buckets-for-full-packet-captures`

Validates buckets added to the packet captures API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic-visibility-pcaps_pcaps_ownership_validate_request](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-ownership-validate-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Validate buckets for full packet captures response. |
| default | Validate buckets for full packet captures response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_ownership_single_response](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-ownership-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
