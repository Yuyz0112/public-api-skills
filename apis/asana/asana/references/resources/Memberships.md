# Memberships

A membership object represents the relationship between a team or user and an object in Asana. Currently, the
supported types of memberships are for goals, projects, and portfolios. For example, a project membership
can be used to add a user to a project.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/memberships` | Get multiple memberships | [View](../operations/getMemberships.md) |
| POST | `/memberships` | Create a membership | [View](../operations/createMembership.md) |
| GET | `/memberships/{membership_gid}` | Get a membership | [View](../operations/getMembership.md) |
| PUT | `/memberships/{membership_gid}` | Update a membership | [View](../operations/updateMembership.md) |
| DELETE | `/memberships/{membership_gid}` | Delete a membership | [View](../operations/deleteMembership.md) |
