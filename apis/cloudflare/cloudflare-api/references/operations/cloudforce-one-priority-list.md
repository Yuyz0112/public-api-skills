# POST /accounts/{account_id}/cloudforce-one/requests/priority

**Resource:** [Priority Intelligence Requirements (PIR)](../resources/Priority-Intelligence-Requirements-PIR.md)
**List Priority Intelligence Requirements**
**Operation ID:** `cloudforce-one-priority-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_priority-list](../schemas/cloudforce-one-requests/cloudforce-one-requests-priority-list.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | List priorities response. |
| 4XX | List priorities response failure. |

## Security

- **api_email**
- **api_key**
