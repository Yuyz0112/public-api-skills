# TweetNotice

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | string | Yes | If the label is being applied or removed. Possible values are ‘apply’ or ‘remove’. |
| `details` | string | No | Information shown on the Tweet label |
| `event_at` | string (date-time) | Yes | Event time. |
| `event_type` | string | Yes | The type of label on the Tweet |
| `extended_details_url` | string | No | Link to more information about this kind of label |
| `label_title` | string | No | Title/header of the Tweet label |
| `tweet` | object | Yes |  |

## Nested Fields

### `tweet`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_id` | [UserId](UserId.md) | Yes |  |
| `id` | [TweetId](TweetId.md) | Yes |  |

