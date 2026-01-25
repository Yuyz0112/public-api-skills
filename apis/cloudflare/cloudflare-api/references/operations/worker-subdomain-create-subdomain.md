# PUT /accounts/{account_id}/workers/subdomain

**Resource:** [Worker Subdomain](../resources/Worker-Subdomain.md)
**Create Subdomain**
**Operation ID:** `worker-subdomain-create-subdomain`

Creates a Workers subdomain for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_schemas-subdomain](../schemas/workers/workers-schemas-subdomain.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Subdomain response. |
| 4XX | Create Subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
