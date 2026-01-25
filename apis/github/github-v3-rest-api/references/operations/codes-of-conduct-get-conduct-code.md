# GET /codes_of_conduct/{key}

**Resource:** [codes-of-conduct](../resources/codes-of-conduct.md)
**Get a code of conduct**
**Operation ID:** `codes-of-conduct/get-conduct-code`

Returns information about the specified GitHub code of conduct.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-of-conduct](../schemas/code-of-conduct/code-of-conduct.md)

