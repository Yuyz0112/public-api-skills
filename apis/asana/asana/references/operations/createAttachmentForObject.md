# POST /attachments

**Resource:** [Attachments](../resources/Attachments.md)
**Upload an attachment**
**Operation ID:** `createAttachmentForObject`

<b>Required scope: </b><code>attachments:write</code>

Upload an attachment.

This method uploads an attachment on an object and returns the compact
record for the created attachment object. This is possible by either:

- Providing the URL of the external resource being attached, or
- Downloading the file content first and then uploading it as any other attachment. Note that it is not possible to attach
files from third party services such as Dropbox, Box, Vimeo & Google Drive via the API

The 100MB size limit on attachments in Asana is enforced on this endpoint.

This endpoint expects a multipart/form-data encoded request containing the full contents of the file to be uploaded.

Requests made should follow the HTTP/1.1 specification that line
terminators are of the form `CRLF` or `\r\n` outlined
[here](http://www.w3.org/Protocols/HTTP/1.1/draft-ietf-http-v11-spec-01#Basic-Rules) in order for the server to reliably and properly handle the request.

For file names that contain non-ASCII characters, the file name should be URL-encoded. For example, a file named `résumé.pdf` should be encoded as
`r%C3%A9sum%C3%A9.pdf` and the `filename` parameter in the `Content-Disposition` header should be set to the encoded file name.

Below is an example of a cURL request with the `Content-Disposition` header:

```
export ASANA_PAT="<YOUR_ASANA_PERSONAL_ACCESS_TOKEN>"
export PARENT_ID="<PARENT_GID>"
export ENCODED_NAME="r%C3%A9sum%C3%A9.pdf"
curl --location 'https://app.asana.com/api/1.0/attachments' \
  --header 'Content-Type: multipart/form-data' \
  --header 'Accept: application/json' \
  --header "Authorization: Bearer $ASANA_PAT" \
  --form "parent=$PARENT_ID" \
  --form "file=@/Users/exampleUser/Downloads/résumé.pdf;headers=\"Content-Disposition: form-data; name="file"; filename="$ENCODED_NAME.pdf"; filename*=UTF-8''$ENCODED_NAME.pdf\""
```

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The file you want to upload.

*Note when using curl:*

Be sure to add an `‘@’` before the file path, and use the `--form`
option instead of the `-d` option.

When uploading PDFs with curl, force the content-type to be pdf by
appending the content type to the file path: `--form
"file=@file.pdf;type=application/pdf"`.

**Content Types:** `multipart/form-data`

**Schema:** [AttachmentRequest](../schemas/Attachment/AttachmentRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully uploaded the attachment to the parent object. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: attachments:write
