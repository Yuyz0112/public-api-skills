# GET /v1/terminal/locations/{location}

**Resource:** [terminal](../resources/terminal.md)
**Retrieve a Location**
**Operation ID:** `GetTerminalLocationsLocation`

<p>Retrieves a <code>Location</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `location` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

