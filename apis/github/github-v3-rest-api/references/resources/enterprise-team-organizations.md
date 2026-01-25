# enterprise-team-organizations

Endpoints to manage GitHub Enterprise Team organization assignments.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations` | Get organization assignments | [View](../operations/enterprise-team-organizations-get-assignments.md) |
| POST | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations/add` | Add organization assignments | [View](../operations/enterprise-team-organizations-bulk-add.md) |
| POST | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations/remove` | Remove organization assignments | [View](../operations/enterprise-team-organizations-bulk-remove.md) |
| GET | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations/{org}` | Get organization assignment | [View](../operations/enterprise-team-organizations-get-assignment.md) |
| PUT | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations/{org}` | Add an organization assignment | [View](../operations/enterprise-team-organizations-add.md) |
| DELETE | `/enterprises/{enterprise}/teams/{enterprise-team}/organizations/{org}` | Delete an organization assignment | [View](../operations/enterprise-team-organizations-delete.md) |
