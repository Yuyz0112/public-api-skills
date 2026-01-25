# Live streams

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/analytics/livestreams/overall` | Fetch complete analytics data for your livestreams | [View](../operations/get-livestream-analytics-complete.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/livestreams` | Fetch all livestreams | [View](../operations/fetch-all-livestreams.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/livestreams` | Create an independent livestream | [View](../operations/post-accounts-account-id-realtime-kit-app-id-livestreams.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/livestreams/sessions/{livestream-session-id}` | Fetch livestream session details using livestream session ID | [View](../operations/get-v2-livestreams-livestream-session-id.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/livestreams/{livestream_id}` | Fetch livestream details using livestream ID | [View](../operations/get-v2-livestream-session-livestream-id.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/livestreams/{livestream_id}/active-livestream-session` | Fetch active livestream session details | [View](../operations/get-v2-active-livestream-session-details.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-livestream` | Fetch active livestreams for a meeting | [View](../operations/get-v2-meetings-meetingId-active-livestream.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-livestream/stop` | Stop livestreaming a meeting | [View](../operations/stop-livestreaming.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/livestream` | Fetch livestream session details for a meeting | [View](../operations/livestream-session-details.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/livestreams` | Start livestreaming a meeting | [View](../operations/start-livestreaming.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/livestream-sessions` | Fetch livestream session details using a session ID | [View](../operations/get-v2-livestreamsession-session-meetingId-active-livestream.md) |
