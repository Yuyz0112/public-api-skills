# GET /gitignore/templates/{name}

**Resource:** [gitignore](../resources/gitignore.md)
**Get a gitignore template**
**Operation ID:** `gitignore/get-template`

Get the content of a gitignore template.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw .gitignore contents.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

**Success Response Schema:**

[gitignore-template](../schemas/gitignore-template/gitignore-template.md)

