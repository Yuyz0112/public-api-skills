# POST /v1/file_links/{link}

**Resource:** [file_links](../resources/file-links.md)
**Update a file link**
**Operation ID:** `PostFileLinksLink`

<p>Updates an existing file link object. Expired links can no longer be updated.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `link` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[file_link](../schemas/file/file-link.md)

