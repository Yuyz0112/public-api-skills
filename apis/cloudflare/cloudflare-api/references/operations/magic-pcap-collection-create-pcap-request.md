# POST /accounts/{account_id}/pcaps

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Create PCAP request**
**Operation ID:** `magic-pcap-collection-create-pcap-request`

Create new PCAP request for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic-visibility-pcaps_pcaps_request_pcap](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-request-pcap.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create PCAP request response. |
| default | Create PCAP request response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_single_response](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
