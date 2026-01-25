# DELETE /accounts/{account_id}/cloudforce-one/events/{dataset_id}/delete

**Resource:** [Event](../resources/Event.md)
**Deletes one or more events**
**Operation ID:** `delete_EventDeleteDO`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |
| `eventIds` | query | string[] | Yes | Array of Event IDs to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the number of deleted events. |
| 400 | Bad Request. |

## Security

- **api_token**
