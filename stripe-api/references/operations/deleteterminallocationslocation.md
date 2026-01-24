# DELETE /v1/terminal/locations/{location}

**Resource:** [terminal](../resources/terminal.md)
**Delete a Location**
**Operation ID:** `DeleteTerminalLocationsLocation`

<p>Deletes a <code>Location</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_terminal.location](../schemas/deleted/deleted-terminal-location.md)

