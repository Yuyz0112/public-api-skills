# GET /accounts/{account_id}/workers/domains

**Resource:** [Worker Domain](../resources/Worker-Domain.md)
**List Domains**
**Operation ID:** `worker-domain-list-domains`

Lists all Worker Domains for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_account_identifier | Yes |  |
| `zone_name` | query | workers_zone_name | No |  |
| `service` | query | workers_schemas-service | No |  |
| `zone_id` | query | workers_zone_identifier | No |  |
| `hostname` | query | string | No |  |
| `environment` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Domains response. |
| 4XX | List Domains response failure. |

**Success Response Schema:**

[workers_domain-response-collection](../schemas/workers/workers-domain-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
