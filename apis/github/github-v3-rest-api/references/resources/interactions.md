# interactions

Owner or admin management of users interactions.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/interaction-limits` | Get interaction restrictions for an organization | [View](../operations/interactions-get-restrictions-for-org.md) |
| PUT | `/orgs/{org}/interaction-limits` | Set interaction restrictions for an organization | [View](../operations/interactions-set-restrictions-for-org.md) |
| DELETE | `/orgs/{org}/interaction-limits` | Remove interaction restrictions for an organization | [View](../operations/interactions-remove-restrictions-for-org.md) |
| GET | `/repos/{owner}/{repo}/interaction-limits` | Get interaction restrictions for a repository | [View](../operations/interactions-get-restrictions-for-repo.md) |
| PUT | `/repos/{owner}/{repo}/interaction-limits` | Set interaction restrictions for a repository | [View](../operations/interactions-set-restrictions-for-repo.md) |
| DELETE | `/repos/{owner}/{repo}/interaction-limits` | Remove interaction restrictions for a repository | [View](../operations/interactions-remove-restrictions-for-repo.md) |
| GET | `/user/interaction-limits` | Get interaction restrictions for your public repositories | [View](../operations/interactions-get-restrictions-for-authenticated-user.md) |
| PUT | `/user/interaction-limits` | Set interaction restrictions for your public repositories | [View](../operations/interactions-set-restrictions-for-authenticated-user.md) |
| DELETE | `/user/interaction-limits` | Remove interaction restrictions from your public repositories | [View](../operations/interactions-remove-restrictions-for-authenticated-user.md) |
