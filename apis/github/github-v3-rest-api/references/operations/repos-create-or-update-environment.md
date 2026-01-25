# PUT /repos/{owner}/{repo}/environments/{environment_name}

**Resource:** [repos](../resources/repos.md)
**Create or update an environment**
**Operation ID:** `repos/create-or-update-environment`

Create or update an environment with protection rules, such as required reviewers. For more information about environment protection rules, see "[Environments](/actions/reference/environments#environment-protection-rules)."

> [!NOTE]
> To create or update name patterns that branches must match in order to deploy to this environment, see "[Deployment branch policies](/rest/deployments/branch-policies)."

> [!NOTE]
> To create or update secrets for an environment, see "[GitHub Actions secrets](/rest/actions/secrets)."

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | Validation error when the environment name is invalid or when `protected_branches` and `custom_branch_policies` in `deployment_branch_policy` are set to the same value |

**Success Response Schema:**

[environment](../schemas/environment/environment.md)

