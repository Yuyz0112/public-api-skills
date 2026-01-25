# realtimekit_ParticipantQualityStats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `quality_stats` | object[] | No |  |

## Nested Fields

### `quality_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio_bandwidth` | number | No |  |
| `audio_packet_loss` | number | No |  |
| `audio_stats` | object[] | No |  |
| `average_quality` | number | No |  |
| `end` | string | No |  |
| `peer_id` | string | No |  |
| `start` | string | No |  |
| `video_bandwidth` | number | No |  |
| `video_packet_loss` | number | No |  |
| `video_stats` | object[] | No |  |

#### `quality_stats.audio_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `concealment_events` | number | No |  |
| `jitter` | number | No |  |
| `packets_lost` | number | No |  |
| `quality` | number | No |  |
| `timestamp` | string | No |  |

#### `quality_stats.video_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `frame_height` | number | No |  |
| `frame_width` | number | No |  |
| `frames_dropped` | number | No |  |
| `frames_per_second` | number | No |  |
| `jitter` | number | No |  |
| `packets_lost` | number | No |  |
| `quality` | number | No |  |
| `timestamp` | string | No |  |

