# GET /accounts/{account_id}/access/groups

**Resource:** [Access groups](../resources/Access-groups.md)
**List Access groups**
**Operation ID:** `access-groups-list-access-groups`

Lists all Access groups.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `name` | query | string | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access groups response |
| 4XX | List Access groups response failure |

**Success Response Schema:**

[access_schemas-response_collection](../schemas/access/access-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
