# GET /v1/file_links/{link}

**Resource:** [file_links](../resources/file-links.md)
**Retrieve a file link**
**Operation ID:** `GetFileLinksLink`

<p>Retrieves the file link with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

