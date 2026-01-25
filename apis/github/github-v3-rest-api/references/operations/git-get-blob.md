# GET /repos/{owner}/{repo}/git/blobs/{file_sha}

**Resource:** [git](../resources/git.md)
**Get a blob**
**Operation ID:** `git/get-blob`

The `content` in the response will always be Base64 encoded.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw blob data.
- **`application/vnd.github+json`**: Returns a JSON representation of the blob with `content` as a base64 encoded string. This is the default if no media type is specified.

**Note** This endpoint supports blobs up to 100 megabytes in size.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_sha` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[blob](../schemas/blob/blob.md)

