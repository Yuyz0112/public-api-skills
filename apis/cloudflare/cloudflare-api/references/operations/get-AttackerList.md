# GET /accounts/{account_id}/cloudforce-one/events/attackers

**Resource:** [Attacker](../resources/Attacker.md)
**Lists attackers across multiple datasets**
**Operation ID:** `get_AttackerList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `datasetIds` | query | string[] | No | Array of dataset IDs to query attackers from. If not provided, uses the default dataset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of attackers. |
| 400 | Bad Request. |

## Security

- **api_token**
