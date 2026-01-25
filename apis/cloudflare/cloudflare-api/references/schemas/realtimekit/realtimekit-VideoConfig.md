# realtimekit_VideoConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `codec` | enum: H264, VP8 | No | Codec using which the recording will be encoded. |
| `export_file` | boolean | No | Controls whether to export video file seperately |
| `height` | integer | No | Height of the recording video in pixels |
| `watermark` | object | No | Watermark to be added to the recording |
| `width` | integer | No | Width of the recording video in pixels |

## Nested Fields

### `watermark`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `position` | enum: left top, right top, left bottom... | No | Position of the watermark |
| `size` | object | No | Size of the watermark |
| `url` | string (uri) | No | URL of the watermark image |

#### `watermark.size`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `height` | integer | No | Height of the watermark in px |
| `width` | integer | No | Width of the watermark in px |

