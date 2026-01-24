# DELETE /v1/terminal/readers/{reader}

**Resource:** [terminal](../resources/terminal.md)
**Delete a Reader**
**Operation ID:** `DeleteTerminalReadersReader`

<p>Deletes a <code>Reader</code> object.</p>

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

**Success Response Schema:**

[deleted_terminal.reader](../schemas/deleted/deleted-terminal-reader.md)

