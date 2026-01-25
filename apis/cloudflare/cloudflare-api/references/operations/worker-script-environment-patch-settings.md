# PATCH /accounts/{account_id}/workers/services/{service_name}/environments/{environment_name}/settings

**Resource:** [Worker Environment](../resources/Worker-Environment.md)
**Patch Script Settings**
**Operation ID:** `worker-script-environment-patch-settings`

Patch script metadata, such as bindings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `service_name` | path | workers_service | Yes |  |
| `environment_name` | path | workers_environment | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_script-settings-response](../schemas/workers/workers-script-settings-response.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch script settings. |
| 4XX | Patch script settings failure. |

**Success Response Schema:**

[workers_script-settings-response](../schemas/workers/workers-script-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
