# CommentFragment

An object representing a fragment of a comment left by a user, used in the payload of the `FILE_COMMENT` event. Note only ONE of the fields below will be set

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `text` | string | No | Comment text that is set if a fragment is text based |
| `mention` | string | No | User id that is set if a fragment refers to a user mention |

