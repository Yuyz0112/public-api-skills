# DELETE /accounts/{account_id}/realtime/kit/{app_id}/presets/{preset_id}

**Resource:** [Presets](../resources/Presets.md)
**Delete a preset**
**Operation ID:** `delete-presets-preset_id`

Deletes a preset using the provided preset ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `preset_id` | path | string | Yes | ID of the preset to fetch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
