# enterprise-team-memberships

Endpoints to manage GitHub Enterprise Team memberships.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships` | List members in an enterprise team | [View](../operations/enterprise-team-memberships-list.md) |
| POST | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships/add` | Bulk add team members | [View](../operations/enterprise-team-memberships-bulk-add.md) |
| POST | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships/remove` | Bulk remove team members | [View](../operations/enterprise-team-memberships-bulk-remove.md) |
| GET | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships/{username}` | Get enterprise team membership | [View](../operations/enterprise-team-memberships-get.md) |
| PUT | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships/{username}` | Add team member | [View](../operations/enterprise-team-memberships-add.md) |
| DELETE | `/enterprises/{enterprise}/teams/{enterprise-team}/memberships/{username}` | Remove team membership | [View](../operations/enterprise-team-memberships-remove.md) |
