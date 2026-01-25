# NoteInfo

A X Community Note is a note on a Post.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `classification` | [NoteClassification](NoteClassification.md) | Yes |  |
| `misleading_tags` | MisleadingTags[] | Yes |  |
| `text` | string | Yes | The text summary in the Community Note. |
| `trustworthy_sources` | boolean | Yes | Whether the note provided trustworthy links. |

