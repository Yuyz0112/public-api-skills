# GET /accounts/{account_id}/workers/scripts

**Resource:** [Worker Script](../resources/Worker-Script.md)
**List Workers**
**Operation ID:** `worker-script-list-workers`

Fetch a list of uploaded workers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `tags` | query | string | No | Filter scripts by tags. Format: comma-separated list of tag:allowed pairs where allowed is 'yes' or 'no'. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Workers response. |
| 4XX | List Workers response failure. |

**Success Response Schema:**

[workers_script-response-collection](../schemas/workers/workers-script-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
