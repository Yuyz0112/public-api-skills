# DELETE /repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules/{protection_rule_id}

**Resource:** [repos](../resources/repos.md)
**Disable a custom protection rule for an environment**
**Operation ID:** `repos/disable-deployment-protection-rule`

Disables a custom deployment protection rule for an environment.

The authenticated user must have admin or owner permissions to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

