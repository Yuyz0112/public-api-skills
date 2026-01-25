# PUT /accounts/{account_id}/cloudforce-one/requests/priority/{priority_id}

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**Update a Priority Intelligence Requirement**
**Operation ID:** `cloudforce-one-priority-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `priority_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_priority-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-priority-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update priority response. |
| 4XX | Update priority response failure. |

## Security

- **api_email**
- **api_key**
