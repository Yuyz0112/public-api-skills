# Space

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | Creation time of the Space. |
| `creator_id` | [UserId](UserId.md) | No |  |
| `ended_at` | string (date-time) | No | End time of the Space. |
| `host_ids` | UserId[] | No | The user ids for the hosts of the Space. |
| `id` | [SpaceId](SpaceId.md) | Yes |  |
| `invited_user_ids` | UserId[] | No | An array of user ids for people who were invited to a Space. |
| `is_ticketed` | boolean | No | Denotes if the Space is a ticketed Space. |
| `lang` | string | No | The language of the Space. |
| `participant_count` | integer (int32) | No | The number of participants in a Space. |
| `scheduled_start` | string (date-time) | No | A date time stamp for when a Space is scheduled to begin. |
| `speaker_ids` | UserId[] | No | An array of user ids for people who were speakers in a Space. |
| `started_at` | string (date-time) | No | When the Space was started as a date string. |
| `state` | enum: live, scheduled, ended | Yes | The current state of the Space. |
| `subscriber_count` | integer (int32) | No | The number of people who have either purchased a ticket or set a reminder for this Space. |
| `title` | string | No | The title of the Space. |
| `topics` | object[] | No | The topics of a Space, as selected by its creator. |
| `updated_at` | string (date-time) | No | When the Space was last updated. |

## Nested Fields

### `topics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the given topic. |
| `id` | string | Yes | An ID suitable for use in the REST API. |
| `name` | string | Yes | The name of the given topic. |

