# Deploy resources

Operations related to deploy resources.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/users/{user_id}/project_deploy_keys` | Get the project-level Deploy keys that a specified user can access to. | [View](../operations/getApiV4UsersUserIdProjectDeployKeys.md) |
| GET | `/api/v4/projects/{id}/deployments` | List project deployments | [View](../operations/getApiV4ProjectsIdDeployments.md) |
| POST | `/api/v4/projects/{id}/deployments` | Create a deployment | [View](../operations/postApiV4ProjectsIdDeployments.md) |
| GET | `/api/v4/projects/{id}/deployments/{deployment_id}` | Get a specific deployment | [View](../operations/getApiV4ProjectsIdDeploymentsDeploymentId.md) |
| PUT | `/api/v4/projects/{id}/deployments/{deployment_id}` | Update a deployment | [View](../operations/putApiV4ProjectsIdDeploymentsDeploymentId.md) |
| DELETE | `/api/v4/projects/{id}/deployments/{deployment_id}` | Delete a specific deployment | [View](../operations/deleteApiV4ProjectsIdDeploymentsDeploymentId.md) |
| GET | `/api/v4/projects/{id}/deployments/{deployment_id}/merge_requests` | List of merge requests associated with a deployment | [View](../operations/getApiV4ProjectsIdDeploymentsDeploymentIdMergeRequests.md) |
| POST | `/api/v4/projects/{id}/deployments/{deployment_id}/approval` | Approve or reject a blocked deployment | [View](../operations/postApiV4ProjectsIdDeploymentsDeploymentIdApproval.md) |
| GET | `/api/v4/deploy_tokens` | List all deploy tokens | [View](../operations/getApiV4DeployTokens.md) |
| GET | `/api/v4/projects/{id}/deploy_tokens` | List project deploy tokens | [View](../operations/getApiV4ProjectsIdDeployTokens.md) |
| POST | `/api/v4/projects/{id}/deploy_tokens` | Create a project deploy token | [View](../operations/postApiV4ProjectsIdDeployTokens.md) |
| GET | `/api/v4/projects/{id}/deploy_tokens/{token_id}` | Get a project deploy token | [View](../operations/getApiV4ProjectsIdDeployTokensTokenId.md) |
| DELETE | `/api/v4/projects/{id}/deploy_tokens/{token_id}` | Delete a project deploy token | [View](../operations/deleteApiV4ProjectsIdDeployTokensTokenId.md) |
| GET | `/api/v4/groups/{id}/deploy_tokens` | List group deploy tokens | [View](../operations/getApiV4GroupsIdDeployTokens.md) |
| POST | `/api/v4/groups/{id}/deploy_tokens` | Create a group deploy token | [View](../operations/postApiV4GroupsIdDeployTokens.md) |
| GET | `/api/v4/groups/{id}/deploy_tokens/{token_id}` | Get a group deploy token | [View](../operations/getApiV4GroupsIdDeployTokensTokenId.md) |
| DELETE | `/api/v4/groups/{id}/deploy_tokens/{token_id}` | Delete a group deploy token | [View](../operations/deleteApiV4GroupsIdDeployTokensTokenId.md) |
| GET | `/api/v4/deploy_keys` | List all deploy keys | [View](../operations/getApiV4DeployKeys.md) |
| POST | `/api/v4/deploy_keys` | Create a deploy key | [View](../operations/postApiV4DeployKeys.md) |
| GET | `/api/v4/projects/{id}/deploy_keys` | List deploy keys for project | [View](../operations/getApiV4ProjectsIdDeployKeys.md) |
| POST | `/api/v4/projects/{id}/deploy_keys` | Add deploy key | [View](../operations/postApiV4ProjectsIdDeployKeys.md) |
| GET | `/api/v4/projects/{id}/deploy_keys/{key_id}` | Get a single deploy key | [View](../operations/getApiV4ProjectsIdDeployKeysKeyId.md) |
| PUT | `/api/v4/projects/{id}/deploy_keys/{key_id}` | Update deploy key | [View](../operations/putApiV4ProjectsIdDeployKeysKeyId.md) |
| DELETE | `/api/v4/projects/{id}/deploy_keys/{key_id}` | Delete deploy key | [View](../operations/deleteApiV4ProjectsIdDeployKeysKeyId.md) |
| POST | `/api/v4/projects/{id}/deploy_keys/{key_id}/enable` | Enable a deploy key | [View](../operations/postApiV4ProjectsIdDeployKeysKeyIdEnable.md) |
