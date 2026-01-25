# PUT /accounts/{account_id}/workers/services/{service_name}/environments/{environment_name}/content

**Resource:** [Worker Environment](../resources/Worker-Environment.md)
**Put script content**
**Operation ID:** `worker-environment-put-script-content`

Put script content from a worker with an environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `service_name` | path | workers_service | Yes |  |
| `environment_name` | path | workers_environment | Yes |  |
| `CF-WORKER-BODY-PART` | header | string | No | The multipart name of a script upload part containing script content in service worker format. Alternative to including in a metadata part. |
| `CF-WORKER-MAIN-MODULE-PART` | header | string | No | The multipart name of a script upload part containing script content in es module format. Alternative to including in a metadata part. |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Put script content. |
| 4XX | Put script content failure. |

**Success Response Schema:**

[workers_script-response-single](../schemas/workers/workers-script-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
