# PUT /accounts/{account_id}/workers/scripts/{script_name}/content

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Put script content**
**Operation ID:** `worker-script-put-content`

Put script content without touching config or metadata.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
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
