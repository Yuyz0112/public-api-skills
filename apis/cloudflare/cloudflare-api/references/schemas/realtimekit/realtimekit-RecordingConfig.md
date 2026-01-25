# realtimekit_RecordingConfig

Recording Configurations to be used for this meeting. This level of configs takes higher preference over App level configs on the RealtimeKit developer portal.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio_config` | [realtimekit_AudioConfig](realtimekit-AudioConfig.md) | No |  |
| `file_name_prefix` | string | No | Adds a prefix to the beginning of the file name of the recording. |
| `live_streaming_config` | [realtimekit_LivestreamingConfig](realtimekit-LivestreamingConfig.md) | No |  |
| `max_seconds` | number | No | Specifies the maximum duration for recording in seconds, ranging from a minimum of 60 seconds to a maximum of 24 hours. |
| `realtimekit_bucket_config` | [realtimekit_realtimekitBucketConfig](realtimekit-realtimekitBucketConfig.md) | No |  |
| `storage_config` | [realtimekit_StorageConfig](realtimekit-StorageConfig.md) | No |  |
| `video_config` | [realtimekit_VideoConfig](realtimekit-VideoConfig.md) | No |  |

