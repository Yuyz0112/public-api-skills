# Sessions

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions` | Fetch all sessions of an App | [View](../operations/GetSessions.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/peer-report/{peer_id}` | Fetch details of peer | [View](../operations/GetParticipantDataFromPeerId.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}` | Fetch details of a session | [View](../operations/GetSessionDetails.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/chat` | Fetch all chat messages of a session | [View](../operations/GetSessionChat.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/participants` | Fetch participants list of a session | [View](../operations/GetSessionParticipants.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/participants/{participant_id}` | Fetch details of a participant | [View](../operations/GetParticipantDetails.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/summary` | Fetch summary of transcripts for a session | [View](../operations/GetSessionSummary.md) |
| POST | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/summary` | Generate summary of Transcripts for the session | [View](../operations/post-sessions-session-id-summary.md) |
| GET | `/accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/transcript` | Fetch the complete transcript for a session | [View](../operations/GetSessionTranscript.md) |
