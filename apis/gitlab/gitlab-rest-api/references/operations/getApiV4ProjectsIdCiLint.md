# GET /api/v4/projects/{id}/ci/lint

**Resource:** [CI lint](../resources/CI-lint.md)
**Validates a CI YAML configuration with a namespace**
**Operation ID:** `getApiV4ProjectsIdCiLint`

Checks if a project’s .gitlab-ci.yml configuration in a given commit (by default HEAD of the
        project’s default branch) is valid

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sha` | query | string | No | Deprecated: Use content_ref instead |
| `content_ref` | query | string | No | The CI/CD configuration content is taken from this commit SHA, branch or tag. Defaults to the HEAD of the project's default branch |
| `dry_run` | query | boolean | No | Run pipeline creation simulation, or only do static check. This is false by default |
| `include_jobs` | query | boolean | No | If the list of jobs that would exist in a static check or pipeline
        simulation should be included in the response. This is false by default |
| `ref` | query | string | No | Deprecated: Use dry_run_ref instead |
| `dry_run_ref` | query | string | No | Branch or tag used as context when executing a dry run. Defaults to the default branch of the project. Only used when dry_run is true |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiLintResult](../schemas/APIEntitiesCiLintResult/APIEntitiesCiLintResult.md)

