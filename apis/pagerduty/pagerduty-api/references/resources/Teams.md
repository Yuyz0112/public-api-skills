# Teams

A team is a collection of Users and Escalation Policies that represent a group of people within an organization.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/teams` | List teams | [View](../operations/listTeams.md) |
| POST | `/teams` | Create a team | [View](../operations/createTeam.md) |
| GET | `/teams/{id}` | Get a team | [View](../operations/getTeam.md) |
| PUT | `/teams/{id}` | Update a team | [View](../operations/updateTeam.md) |
| DELETE | `/teams/{id}` | Delete a team | [View](../operations/deleteTeam.md) |
| GET | `/teams/{id}/audit/records` | List audit records for a team | [View](../operations/listTeamsAuditRecords.md) |
| PUT | `/teams/{id}/escalation_policies/{escalation_policy_id}` | Add an escalation policy to a team | [View](../operations/updateTeamEscalationPolicy.md) |
| DELETE | `/teams/{id}/escalation_policies/{escalation_policy_id}` | Remove an escalation policy from a team | [View](../operations/deleteTeamEscalationPolicy.md) |
| GET | `/teams/{id}/members` | List members of a team | [View](../operations/listTeamUsers.md) |
| GET | `/teams/{id}/notification_subscriptions` | List Team Notification Subscriptions | [View](../operations/getTeamNotificationSubscriptions.md) |
| POST | `/teams/{id}/notification_subscriptions` | Create Team Notification Subscriptions | [View](../operations/createTeamNotificationSubscriptions.md) |
| POST | `/teams/{id}/notification_subscriptions/unsubscribe` |  | [View](../operations/removeTeamNotificationSubscriptions.md) |
| PUT | `/teams/{id}/users/{user_id}` | Add a user to a team | [View](../operations/updateTeamUser.md) |
| DELETE | `/teams/{id}/users/{user_id}` | Remove a user from a team | [View](../operations/deleteTeamUser.md) |
