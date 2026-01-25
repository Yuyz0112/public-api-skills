# PUT /accounts/{account_id}/workers/domains

**Resource:** [Worker Domain](../resources/Worker-Domain.md)
**Attach to Domain**
**Operation ID:** `worker-domain-attach-to-domain`

Attaches a Worker to a zone and hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Attach to Domain response. |
| 4XX | Attach to Domain response failure. |

**Success Response Schema:**

[workers_domain-response-single](../schemas/workers/workers-domain-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
