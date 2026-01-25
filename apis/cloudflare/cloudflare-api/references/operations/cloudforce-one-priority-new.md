# POST /accounts/{account_id}/cloudforce-one/requests/priority/new

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**Create a New Priority Intelligence Requirement**
**Operation ID:** `cloudforce-one-priority-new`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_priority-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-priority-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create priority response. |
| 4XX | Create priority response  failure. |

## Security

- **api_email**
- **api_key**
