# GET /repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies/{branch_policy_id}

**Resource:** [repos](../resources/repos.md)
**Get a deployment branch policy**
**Operation ID:** `repos/get-deployment-branch-policy`

Gets a deployment branch or tag policy for an environment.

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[deployment-branch-policy](../schemas/deployment-branch-policy/deployment-branch-policy.md)

