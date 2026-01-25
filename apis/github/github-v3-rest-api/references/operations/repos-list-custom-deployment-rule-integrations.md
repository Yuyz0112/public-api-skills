# GET /repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules/apps

**Resource:** [repos](../resources/repos.md)
**List custom deployment rule integrations available for an environment**
**Operation ID:** `repos/list-custom-deployment-rule-integrations`

Gets all custom deployment protection rule integrations that are available for an environment.

The authenticated user must have admin or owner permissions to the repository to use this endpoint.

For more information about environments, see "[Using environments for deployment](https://docs.github.com/actions/deployment/targeting-different-environments/using-environments-for-deployment)."

For more information about the app that is providing this custom deployment rule, see "[GET an app](https://docs.github.com/rest/apps/apps#get-an-app)".

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of custom deployment rule integrations available for this environment. |

