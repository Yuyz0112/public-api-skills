# GET /accounts/{account_id}/intel/domain

**Resource:** [Domain Intelligence](../resources/Domain-Intelligence.md)
**Get Domain Details**
**Operation ID:** `domain-intelligence-get-domain-details`

Gets security details and statistics about a domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |
| `domain` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Domain Details response. |
| 4XX | Get Domain Details response failure. |

**Success Response Schema:**

[intel_single_response](../schemas/intel/intel-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
