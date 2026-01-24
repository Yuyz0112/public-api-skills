# GET /v1/terminal/readers/{reader}

**Resource:** [terminal](../resources/terminal.md)
**Retrieve a Reader**
**Operation ID:** `GetTerminalReadersReader`

<p>Retrieves a <code>Reader</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `reader` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

