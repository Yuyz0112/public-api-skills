# GET /v1/terminal/configurations/{configuration}

**Resource:** [terminal](../resources/terminal.md)
**Retrieve a Configuration**
**Operation ID:** `GetTerminalConfigurationsConfiguration`

<p>Retrieves a <code>Configuration</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `configuration` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

