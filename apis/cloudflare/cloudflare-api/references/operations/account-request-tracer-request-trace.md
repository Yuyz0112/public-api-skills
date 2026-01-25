# POST /accounts/{account_id}/request-tracer/trace

**Resource:** [Account Request Tracer](../resources/Account-Request-Tracer.md)
**Request Trace**
**Operation ID:** `account-request-tracer-request-trace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | request-tracer_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Request Trace response |
| 4XX | Request Trace response failure |

## Security

- **api_email**
- **api_key**
