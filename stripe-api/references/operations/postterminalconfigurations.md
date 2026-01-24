# POST /v1/terminal/configurations

**Resource:** [terminal](../resources/terminal.md)
**Create a Configuration**
**Operation ID:** `PostTerminalConfigurations`

<p>Creates a new <code>Configuration</code> object.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.configuration](../schemas/terminal-configuration/terminal-configuration.md)

