# DELETE /accounts/{account_id}/cloudforce-one/requests/priority/{priority_id}

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**Delete a Priority Intelligence Requirement**
**Operation ID:** `cloudforce-one-priority-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `priority_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete priority response. |
| 4XX | Delete priority response failure. |

**Success Response Schema:**

[cloudforce-one-requests_api-response-common](../schemas/cloudforce-one-requests/cloudforce-one-requests-api-response-common.md)

## Security

- **api_email**
- **api_key**
