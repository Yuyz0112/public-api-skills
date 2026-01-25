# Recordings

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/recordings` | Fetch all recordings for an App | [View](../operations/get-all-recordings.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/recordings` | Start recording a meeting | [View](../operations/start-recording.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/recordings/active-recording/{meeting_id}` | Fetch active recording | [View](../operations/get-active-recording.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/recordings/track` | Start recording audio and video tracks | [View](../operations/startTrackRecordingForAMeeting.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/recordings/{recording_id}` | Fetch details of a recording | [View](../operations/get-one-recording.md) |
| PUT | `/accounts/{account_id}/realtime/kit/{app_id}/recordings/{recording_id}` | Pause/Resume/Stop recording | [View](../operations/pause-resume-stop-recording.md) |
