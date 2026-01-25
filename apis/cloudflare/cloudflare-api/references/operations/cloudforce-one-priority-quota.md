# GET /accounts/{account_id}/cloudforce-one/requests/priority/quota

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**Get Priority Intelligence Requirement Quota**
**Operation ID:** `cloudforce-one-priority-quota`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get priority quota response. |
| 4XX | Get priority quota response failure. |

## Security

- **api_email**
- **api_key**
