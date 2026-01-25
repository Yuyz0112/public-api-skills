# realtimekit_AudioConfig

Object containing configuration regarding the audio that is being recorded.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channel` | enum: mono, stereo | No | Audio signal pathway within an audio file that carries a specific sound source. |
| `codec` | enum: MP3, AAC | No | Codec using which the recording will be encoded. If VP8/VP9 is selected for videoConfig, changing audioConfig is not allowed. In this case, the codec in the audioConfig is automatically set to vorbis. |
| `export_file` | boolean | No | Controls whether to export audio file seperately |

