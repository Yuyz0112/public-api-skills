# PUT /repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies/{branch_policy_id}

**Resource:** [repos](../resources/repos.md)
**Update a deployment branch policy**
**Operation ID:** `repos/update-deployment-branch-policy`

Updates a deployment branch or tag policy for an environment.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [deployment-branch-policy-name-pattern](../schemas/deployment-branch-policy-name-pattern/deployment-branch-policy-name-pattern.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[deployment-branch-policy](../schemas/deployment-branch-policy/deployment-branch-policy.md)

