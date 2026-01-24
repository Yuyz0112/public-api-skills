# POST /v1/files

**Resource:** [files](../resources/files.md)
**Create a file**
**Operation ID:** `PostFiles`

<p>To upload a file to Stripe, you need to send a request of type <code>multipart/form-data</code>. Include the file you want to upload in the request, and the parameters for creating a file.</p>

<p>All of Stripe’s officially supported Client libraries support sending <code>multipart/form-data</code>.</p>

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[file](../schemas/file/file.md)

