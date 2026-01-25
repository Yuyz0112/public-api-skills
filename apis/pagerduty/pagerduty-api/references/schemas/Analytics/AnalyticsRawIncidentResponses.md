# AnalyticsRawIncidentResponses

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `responder_name` | string | No | Name of the user associated with the Incident Response. |
| `responder_id` | string | No | ID of the user associated with the Incident Response. |
| `response_status` | enum: joined, pending, declined | No | Status of the user's interaction with the Incident notification. |
| `responder_type` | enum: assigned, reassigned, escalated... | No | Type of responder, where `assigned` means the user was added to the Incident via Assignment at Incident creation,
`reassigned` means the user was added to the Incident via Reassignment, `escalated` means the user was added via Escalation,
and `added_responder` means the user was added via Responder Reqeuest. |
| `requested_at` | string | No | Timestamp of when the user was requested. |
| `responded_at` | string | No | Timestamp of when the user responded to the request. |
| `time_to_respond_seconds` | integer | No | Measures the time it took for the user to respond to the Incident request. In other words, `responded_at - requested_at`. |

