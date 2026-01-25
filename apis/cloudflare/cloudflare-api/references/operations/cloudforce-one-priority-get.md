# GET /accounts/{account_id}/cloudforce-one/requests/priority/{priority_id}

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**Get a Priority Intelligence Requirement**
**Operation ID:** `cloudforce-one-priority-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `priority_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get priority response. |
| 4XX | Get priority response failure. |

## Security

- **api_email**
- **api_key**
