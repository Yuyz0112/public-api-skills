# POST /accounts/{account_id}/images/v1

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Upload an image**
**Operation ID:** `cloudflare-images-upload-an-image-via-url`

Upload an image with up to 10 Megabytes using a single HTTP POST (multipart/form-data) request.
An image can be uploaded by sending an image file or passing an accessible to an API url.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [images_image_basic_upload](../schemas/images/images-image-basic-upload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload an image response |
| 4XX | Upload an image response failure |

**Success Response Schema:**

[images_image_response_single](../schemas/images/images-image-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
