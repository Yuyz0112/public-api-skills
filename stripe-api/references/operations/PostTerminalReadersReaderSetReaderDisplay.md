# POST /v1/terminal/readers/{reader}/set_reader_display

**Resource:** [terminal](../resources/terminal.md)
**Set reader display**
**Operation ID:** `PostTerminalReadersReaderSetReaderDisplay`

<p>Sets the reader display to show <a href="/docs/terminal/features/display">cart details</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `reader` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.reader](../schemas/terminal-reader/terminal-reader.md)

