# stream_media_status

Specifies a detailed status for a video. If the `state` is `inprogress` or `error`, the `step` field returns `encoding` or `manifest`. If the `state` is `inprogress`, `pctComplete` returns a number between 0 and 100 to indicate the approximate percent of completion. If the `state` is `error`, `errorReasonCode` and `errorReasonText` provide additional details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errorReasonCode` | [stream_errorReasonCode](stream-errorReasonCode.md) | No |  |
| `errorReasonText` | [stream_errorReasonText](stream-errorReasonText.md) | No |  |
| `pctComplete` | [stream_pctComplete](stream-pctComplete.md) | No |  |
| `state` | [stream_media_state](stream-media-state.md) | No |  |

