# Meetings

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings` | Fetch all meetings for an App | [View](../operations/get-all-meetings.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/meetings` | Create a meeting | [View](../operations/create-meeting.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}` | Fetch a meeting for an App | [View](../operations/get-meeting.md) |
| PUT | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}` | Replace a meeting | [View](../operations/replace-meeting.md) |
| PATCH | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}` | Update a meeting | [View](../operations/update-meeting.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants` | Fetch all participants of a meeting | [View](../operations/get-meeting-participants.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants` | Add a participant | [View](../operations/add-participant.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}` | Fetch a participant's detail | [View](../operations/get-meeting-participant.md) |
| DELETE | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}` | Delete a participant | [View](../operations/delete-meeting-participant.md) |
| PATCH | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}` | Edit a participant's detail | [View](../operations/edit-participant.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}/token` | Refresh participant's authentication token | [View](../operations/regenerate-token.md) |
