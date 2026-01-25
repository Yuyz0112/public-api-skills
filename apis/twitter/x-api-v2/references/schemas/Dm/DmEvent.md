# DmEvent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attachments` | object | No | Specifies the type of attachments (if any) present in this DM. |
| `cashtags` | CashtagEntity[] | No |  |
| `created_at` | string (date-time) | No |  |
| `dm_conversation_id` | [DmConversationId](DmConversationId.md) | No |  |
| `event_type` | string | Yes |  |
| `hashtags` | HashtagEntity[] | No |  |
| `id` | [DmEventId](DmEventId.md) | Yes |  |
| `mentions` | MentionEntity[] | No |  |
| `participant_ids` | UserId[] | No | A list of participants for a ParticipantsJoin or ParticipantsLeave event_type. |
| `referenced_tweets` | object[] | No | A list of Posts this DM refers to. |
| `sender_id` | [UserId](UserId.md) | No |  |
| `text` | string | No |  |
| `urls` | UrlEntityDm[] | No |  |

## Nested Fields

### `attachments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_ids` | string[] | No | A list of card IDs (if cards are attached). |
| `media_keys` | MediaKey[] | No | A list of Media Keys for each one of the media attachments (if media are attached). |

### `referenced_tweets`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [TweetId](TweetId.md) | Yes |  |

