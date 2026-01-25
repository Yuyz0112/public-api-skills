# POST /v1/terminal/readers/{reader}

**Resource:** [terminal](../resources/terminal.md)
**Update a Reader**
**Operation ID:** `PostTerminalReadersReader`

<p>Updates a <code>Reader</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `reader` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

