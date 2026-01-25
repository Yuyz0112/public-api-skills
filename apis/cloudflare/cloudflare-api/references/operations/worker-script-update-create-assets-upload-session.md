# POST /accounts/{account_id}/workers/scripts/{script_name}/assets-upload-session

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Create Assets Upload Session**
**Operation ID:** `worker-script-update-create-assets-upload-session`

Start uploading a collection of assets for use in a Worker version. To learn more about the direct uploads of assets, see https://developers.cloudflare.com/workers/static-assets/direct-upload/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_create-assets-upload-session-object](../schemas/workers/workers-create-assets-upload-session-object.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Assets Upload Session response. |
| 4XX | Create Assets Upload Session response failure. |

**Success Response Schema:**

[workers_create-assets-upload-session-response](../schemas/workers/workers-create-assets-upload-session-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
