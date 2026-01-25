# CreateNoteRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `info` | [NoteInfo](NoteInfo.md) | Yes |  |
| `post_id` | [TweetId](TweetId.md) | Yes |  |
| `test_mode` | boolean | Yes | If true, the note being submitted is only for testing the capability of the bot, and won't be publicly visible. If false, the note being submitted will be a new proposed note on the product. |

