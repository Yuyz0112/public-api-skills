# DELETE /2/dm_events/{event_id}

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Delete DM event**
**Operation ID:** `deleteDirectMessagesEvents`

Deletes a specific direct message event by its ID, if owned by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | DmEventId | Yes | The ID of the direct-message event to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[DeleteDmResponse](../schemas/Delete/DeleteDmResponse.md)

## Security

- **OAuth2UserToken**: dm.read, dm.write
- **UserToken**
