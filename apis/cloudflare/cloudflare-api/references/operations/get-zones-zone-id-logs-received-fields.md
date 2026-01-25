# GET /zones/{zone_id}/logs/received/fields

**Resource:** [Logs Received](../resources/Logs-Received.md)
**List fields**
**Operation ID:** `get-zones-zone_id-logs-received-fields`

Lists all fields available. The response is json object with key-value pairs, where keys are field names, and values are descriptions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logshare_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List fields response |
| 4XX | List fields response failure |

**Success Response Schema:**

[logshare_fields_response](../schemas/logshare/logshare-fields-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
