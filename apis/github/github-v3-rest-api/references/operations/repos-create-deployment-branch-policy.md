# POST /repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies

**Resource:** [repos](../resources/repos.md)
**Create a deployment branch policy**
**Operation ID:** `repos/create-deployment-branch-policy`

Creates a deployment branch or tag policy for an environment.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [deployment-branch-policy-name-pattern-with-type](../schemas/deployment-branch-policy-name-pattern-with-type/deployment-branch-policy-name-pattern-with-type.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 303 | Response if the same branch name pattern already exists |
| 404 | Not Found or `deployment_branch_policy.custom_branch_policies` property for the environment is set to false |

**Success Response Schema:**

[deployment-branch-policy](../schemas/deployment-branch-policy/deployment-branch-policy.md)

