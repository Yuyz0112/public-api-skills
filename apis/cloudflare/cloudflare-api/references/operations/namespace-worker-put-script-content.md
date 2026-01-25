# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/content

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Put Script Content**
**Operation ID:** `namespace-worker-put-script-content`

Put script content for a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `CF-WORKER-BODY-PART` | header | string | No | The multipart name of a script upload part containing script content in service worker format. Alternative to including in a metadata part. |
| `CF-WORKER-MAIN-MODULE-PART` | header | string | No | The multipart name of a script upload part containing script content in es module format. Alternative to including in a metadata part. |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Put script content (Workers for Platforms). |
| 4XX | Put script content failure (Workers for Platforms). |

**Success Response Schema:**

[workers_script-response-single](../schemas/workers/workers-script-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
