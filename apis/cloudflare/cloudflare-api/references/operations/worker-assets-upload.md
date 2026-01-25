# POST /accounts/{account_id}/workers/assets/upload

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Upload Assets**
**Operation ID:** `worker-assets-upload`

Upload assets ahead of creating a Worker version.  To learn more about the direct uploads of assets, see https://developers.cloudflare.com/workers/static-assets/direct-upload/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `base64` | query | enum: true | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Upload Assets response. |
| 202 | Upload Assets response. |
| 4XX | Upload Assets response failure. |

**Success Response Schema:**

[workers_completed-upload-assets-response](../schemas/workers/workers-completed-upload-assets-response.md)

## Security

- **assets_jwt**
