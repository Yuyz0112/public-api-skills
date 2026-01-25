# POST /accounts/{account_id}/images/v2/direct_upload

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Create authenticated direct upload URL V2**
**Operation ID:** `cloudflare-images-create-authenticated-direct-upload-url-v-2`

Direct uploads allow users to upload images without API keys. A common use case are web apps, client-side applications, or mobile devices where users upload content directly to Cloudflare Images. This method creates a draft record for a future image. It returns an upload URL and an image identifier. To verify if the image itself has been uploaded, send an image details request (accounts/:account_identifier/images/v1/:identifier), and check that the `draft: true` property is not present.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [images_image_direct_upload_request_v2](../schemas/images/images-image-direct-upload-request-v2.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create authenticated direct upload URL V2 response |
| 4XX | Create authenticated direct upload URL V2 response failure |

**Success Response Schema:**

[images_image_direct_upload_response_v2](../schemas/images/images-image-direct-upload-response-v2.md)

## Security

- **api_token**
- **api_email**
- **api_key**
