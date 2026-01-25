# copilot

Endpoints to manage Copilot using the REST API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/copilot/billing` | Get Copilot seat information and settings for an organization | [View](../operations/copilot-get-copilot-organization-details.md) |
| GET | `/orgs/{org}/copilot/billing/seats` | List all Copilot seat assignments for an organization | [View](../operations/copilot-list-copilot-seats.md) |
| POST | `/orgs/{org}/copilot/billing/selected_teams` | Add teams to the Copilot subscription for an organization | [View](../operations/copilot-add-copilot-seats-for-teams.md) |
| DELETE | `/orgs/{org}/copilot/billing/selected_teams` | Remove teams from the Copilot subscription for an organization | [View](../operations/copilot-cancel-copilot-seat-assignment-for-teams.md) |
| POST | `/orgs/{org}/copilot/billing/selected_users` | Add users to the Copilot subscription for an organization | [View](../operations/copilot-add-copilot-seats-for-users.md) |
| DELETE | `/orgs/{org}/copilot/billing/selected_users` | Remove users from the Copilot subscription for an organization | [View](../operations/copilot-cancel-copilot-seat-assignment-for-users.md) |
| GET | `/orgs/{org}/copilot/metrics` | Get Copilot metrics for an organization | [View](../operations/copilot-copilot-metrics-for-organization.md) |
| GET | `/orgs/{org}/members/{username}/copilot` | Get Copilot seat assignment details for a user | [View](../operations/copilot-get-copilot-seat-details-for-user.md) |
| GET | `/orgs/{org}/team/{team_slug}/copilot/metrics` | Get Copilot metrics for a team | [View](../operations/copilot-copilot-metrics-for-team.md) |
