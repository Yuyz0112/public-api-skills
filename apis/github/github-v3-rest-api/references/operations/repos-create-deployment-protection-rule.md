# POST /repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules

**Resource:** [repos](../resources/repos.md)
**Create a custom deployment protection rule on an environment**
**Operation ID:** `repos/create-deployment-protection-rule`

Enable a custom deployment protection rule for an environment.

The authenticated user must have admin or owner permissions to the repository to use this endpoint.

For more information about the app that is providing this custom deployment rule, see the [documentation for the `GET /apps/{app_slug}` endpoint](https://docs.github.com/rest/apps/apps#get-an-app), as well as the [guide to creating custom deployment protection rules](https://docs.github.com/actions/managing-workflow-runs-and-deployments/managing-deployments/creating-custom-deployment-protection-rules).

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The enabled custom deployment protection rule |

**Success Response Schema:**

[deployment-protection-rule](../schemas/deployment-protection-rule/deployment-protection-rule.md)

