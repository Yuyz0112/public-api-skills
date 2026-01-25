# GET /invites/{code}/target-users/job-status

**Resource:** [invites](../resources/invites.md)
**Operation ID:** `get_invite_target_users_job_status`

Get the target users job status for an invite.

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_invite_target_users_job_status |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[TargetUsersJobStatusResponse](../schemas/Target/TargetUsersJobStatusResponse.md)

## Security

- **BotToken**
