# realtimekit_Recording

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio_download_url` | string (uri) | Yes | If the audio_config is passed, the URL for downloading the audio recording is returned. |
| `download_url` | string (uri) | Yes | URL where the recording can be downloaded. |
| `download_url_expiry` | string (date-time) | Yes | Timestamp when the download URL expires. |
| `file_size` | number | Yes | File size of the recording, in bytes. |
| `id` | string (uuid) | Yes | ID of the recording |
| `invoked_time` | string (date-time) | Yes | Timestamp when this recording was invoked. |
| `output_file_name` | string | Yes | File name of the recording. |
| `recording_duration` | integer | No | Total recording time in seconds. |
| `session_id` | string (uuid) | Yes | ID of the meeting session this recording is for. |
| `started_time` | string (date-time) | Yes | Timestamp when this recording actually started after being invoked. Usually a few seconds after `invoked_time`. |
| `status` | enum: INVOKED, RECORDING, UPLOADING... | Yes | Current status of the recording. |
| `stopped_time` | string (date-time) | Yes | Timestamp when this recording was stopped. Optional; is present only when the recording has actually been stopped. |

