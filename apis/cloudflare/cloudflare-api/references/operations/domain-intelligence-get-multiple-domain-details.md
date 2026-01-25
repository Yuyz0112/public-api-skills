# GET /accounts/{account_id}/intel/domain/bulk

**Resource:** [Domain Intelligence](../resources/Domain-Intelligence.md)
**Get Multiple Domain Details**
**Operation ID:** `domain-intelligence-get-multiple-domain-details`

Same as summary.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |
| `domain` | query | string[] | No | Accepts multiple values like `?domain=cloudflare.com&domain=example.com`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Multiple Domain Details response. |
| 4XX | Get Multiple Domain Details response failure. |

**Success Response Schema:**

[intel_collection_response](../schemas/intel/intel-collection-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
