# DELETE /v1/terminal/configurations/{configuration}

**Resource:** [terminal](../resources/terminal.md)
**Delete a Configuration**
**Operation ID:** `DeleteTerminalConfigurationsConfiguration`

<p>Deletes a <code>Configuration</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `configuration` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_terminal.configuration](../schemas/deleted/deleted-terminal-configuration.md)

