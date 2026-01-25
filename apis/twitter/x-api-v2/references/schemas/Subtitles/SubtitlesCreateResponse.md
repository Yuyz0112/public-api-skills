# SubtitlesCreateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `associated_subtitles` | Subtitles[] | Yes |  |
| `id` | [MediaId](MediaId.md) | Yes |  |
| `media_category` | [MediaCategorySubtitles](MediaCategorySubtitles.md) | Yes |  |

