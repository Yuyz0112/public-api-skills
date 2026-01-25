# teams

Interact with GitHub Teams.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/teams` | List teams | [View](../operations/teams-list.md) |
| POST | `/orgs/{org}/teams` | Create a team | [View](../operations/teams-create.md) |
| GET | `/orgs/{org}/teams/{team_slug}` | Get a team by name | [View](../operations/teams-get-by-name.md) |
| DELETE | `/orgs/{org}/teams/{team_slug}` | Delete a team | [View](../operations/teams-delete-in-org.md) |
| PATCH | `/orgs/{org}/teams/{team_slug}` | Update a team | [View](../operations/teams-update-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/invitations` | List pending team invitations | [View](../operations/teams-list-pending-invitations-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/members` | List team members | [View](../operations/teams-list-members-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/memberships/{username}` | Get team membership for a user | [View](../operations/teams-get-membership-for-user-in-org.md) |
| PUT | `/orgs/{org}/teams/{team_slug}/memberships/{username}` | Add or update team membership for a user | [View](../operations/teams-add-or-update-membership-for-user-in-org.md) |
| DELETE | `/orgs/{org}/teams/{team_slug}/memberships/{username}` | Remove team membership for a user | [View](../operations/teams-remove-membership-for-user-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/repos` | List team repositories | [View](../operations/teams-list-repos-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/repos/{owner}/{repo}` | Check team permissions for a repository | [View](../operations/teams-check-permissions-for-repo-in-org.md) |
| PUT | `/orgs/{org}/teams/{team_slug}/repos/{owner}/{repo}` | Add or update team repository permissions | [View](../operations/teams-add-or-update-repo-permissions-in-org.md) |
| DELETE | `/orgs/{org}/teams/{team_slug}/repos/{owner}/{repo}` | Remove a repository from a team | [View](../operations/teams-remove-repo-in-org.md) |
| GET | `/orgs/{org}/teams/{team_slug}/teams` | List child teams | [View](../operations/teams-list-child-in-org.md) |
| GET | `/teams/{team_id}` | Get a team (Legacy) | [View](../operations/teams-get-legacy.md) |
| DELETE | `/teams/{team_id}` | Delete a team (Legacy) | [View](../operations/teams-delete-legacy.md) |
| PATCH | `/teams/{team_id}` | Update a team (Legacy) | [View](../operations/teams-update-legacy.md) |
| GET | `/teams/{team_id}/invitations` | List pending team invitations (Legacy) | [View](../operations/teams-list-pending-invitations-legacy.md) |
| GET | `/teams/{team_id}/members` | List team members (Legacy) | [View](../operations/teams-list-members-legacy.md) |
| GET | `/teams/{team_id}/members/{username}` | Get team member (Legacy) | [View](../operations/teams-get-member-legacy.md) |
| PUT | `/teams/{team_id}/members/{username}` | Add team member (Legacy) | [View](../operations/teams-add-member-legacy.md) |
| DELETE | `/teams/{team_id}/members/{username}` | Remove team member (Legacy) | [View](../operations/teams-remove-member-legacy.md) |
| GET | `/teams/{team_id}/memberships/{username}` | Get team membership for a user (Legacy) | [View](../operations/teams-get-membership-for-user-legacy.md) |
| PUT | `/teams/{team_id}/memberships/{username}` | Add or update team membership for a user (Legacy) | [View](../operations/teams-add-or-update-membership-for-user-legacy.md) |
| DELETE | `/teams/{team_id}/memberships/{username}` | Remove team membership for a user (Legacy) | [View](../operations/teams-remove-membership-for-user-legacy.md) |
| GET | `/teams/{team_id}/repos` | List team repositories (Legacy) | [View](../operations/teams-list-repos-legacy.md) |
| GET | `/teams/{team_id}/repos/{owner}/{repo}` | Check team permissions for a repository (Legacy) | [View](../operations/teams-check-permissions-for-repo-legacy.md) |
| PUT | `/teams/{team_id}/repos/{owner}/{repo}` | Add or update team repository permissions (Legacy) | [View](../operations/teams-add-or-update-repo-permissions-legacy.md) |
| DELETE | `/teams/{team_id}/repos/{owner}/{repo}` | Remove a repository from a team (Legacy) | [View](../operations/teams-remove-repo-legacy.md) |
| GET | `/teams/{team_id}/teams` | List child teams (Legacy) | [View](../operations/teams-list-child-legacy.md) |
| GET | `/user/teams` | List teams for the authenticated user | [View](../operations/teams-list-for-authenticated-user.md) |
