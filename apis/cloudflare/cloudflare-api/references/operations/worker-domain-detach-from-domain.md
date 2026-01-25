# DELETE /accounts/{account_id}/workers/domains/{domain_id}

**Resource:** [Worker Domain](../resources/Worker-Domain.md)
**Detach from Domain**
**Operation ID:** `worker-domain-detach-from-domain`

Detaches a Worker from a zone and hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_account_identifier | Yes |  |
| `domain_id` | path | workers_domain_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Detach from Domain response. |
| 4XX | Detach from Domain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
