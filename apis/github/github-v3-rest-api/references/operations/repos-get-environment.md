# GET /repos/{owner}/{repo}/environments/{environment_name}

**Resource:** [repos](../resources/repos.md)
**Get an environment**
**Operation ID:** `repos/get-environment`

> [!NOTE]
> To get information about name patterns that branches must match in order to deploy to this environment, see "[Get a deployment branch policy](/rest/deployments/branch-policies#get-a-deployment-branch-policy)."

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[environment](../schemas/environment/environment.md)

