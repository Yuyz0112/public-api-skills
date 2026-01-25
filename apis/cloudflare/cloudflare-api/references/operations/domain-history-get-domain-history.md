# GET /accounts/{account_id}/intel/domain-history

**Resource:** [Domain History](../resources/Domain-History.md)
**Get Domain History**
**Operation ID:** `domain-history-get-domain-history`

Gets historical security threat and content categories currently and previously assigned to a domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |
| `domain` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Domain History response. |
| 4XX | Get Domain History response failure. |

**Success Response Schema:**

[intel_response](../schemas/intel/intel-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
