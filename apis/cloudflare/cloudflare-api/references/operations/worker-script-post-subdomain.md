# POST /accounts/{account_id}/workers/scripts/{script_name}/subdomain

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Post Worker subdomain**
**Operation ID:** `worker-script-post-subdomain`

Enable or disable the Worker on the workers.dev subdomain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Post subdomain response. |
| 4XX | Post subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
