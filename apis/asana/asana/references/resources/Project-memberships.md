# Project memberships

With the introduction of “comment-only” projects in Asana, a user’s membership in a project comes with associated permissions. These permissions (i.e., whether a user has full access to the project or comment-only access) are accessible through the project memberships endpoints described here.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/project_memberships/{project_membership_gid}` | Get a project membership | [View](../operations/getProjectMembership.md) |
| GET | `/projects/{project_gid}/project_memberships` | Get memberships from a project | [View](../operations/getProjectMembershipsForProject.md) |
