# GET /repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules

**Resource:** [repos](../resources/repos.md)
**Get all deployment protection rules for an environment**
**Operation ID:** `repos/get-all-deployment-protection-rules`

Gets all custom deployment protection rules that are enabled for an environment. Anyone with read access to the repository can use this endpoint. For more information about environments, see "[Using environments for deployment](https://docs.github.com/actions/deployment/targeting-different-environments/using-environments-for-deployment)."

For more information about the app that is providing this custom deployment rule, see the [documentation for the `GET /apps/{app_slug}` endpoint](https://docs.github.com/rest/apps/apps#get-an-app).

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of deployment protection rules |

