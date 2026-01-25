# GET /accounts/{account_id}/workers/domains/{domain_id}

**Resource:** [Worker Domain](../resources/Worker-Domain.md)
**Get a Domain**
**Operation ID:** `worker-domain-get-a-domain`

Gets a Worker domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_account_identifier | Yes |  |
| `domain_id` | path | workers_domain_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Domain response. |
| 4XX | Get a Domain response failure. |

**Success Response Schema:**

[workers_domain-response-single](../schemas/workers/workers-domain-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
