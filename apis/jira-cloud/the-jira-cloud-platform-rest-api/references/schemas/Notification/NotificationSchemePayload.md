# NotificationSchemePayload

The payload for creating a notification scheme. The user has to supply the ID for the default notification scheme. For CMP this is provided in the project payload and should be left empty, for TMP it's provided using this payload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the notification scheme |
| `name` | string | No | The name of the notification scheme |
| `notificationSchemeEvents` | NotificationSchemeEventPayload[] | No | The events and notifications for the notification scheme |
| `onConflict` | enum: FAIL, USE, NEW | No | The strategy to use when there is a conflict with an existing entity |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

