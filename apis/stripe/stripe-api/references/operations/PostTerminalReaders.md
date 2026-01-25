# POST /v1/terminal/readers

**Resource:** [terminal](../resources/terminal.md)
**Create a Reader**
**Operation ID:** `PostTerminalReaders`

<p>Creates a new <code>Reader</code> object.</p>

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

