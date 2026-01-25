# webhook-fork

A user forks a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `forkee` | any | Yes | The created [`repository`](https://docs.github.com/rest/repos/repos#get-a-repository) resource. |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

