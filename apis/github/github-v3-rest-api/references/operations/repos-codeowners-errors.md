# GET /repos/{owner}/{repo}/codeowners/errors

**Resource:** [repos](../resources/repos.md)
**List CODEOWNERS errors**
**Operation ID:** `repos/codeowners-errors`

List any syntax errors that are detected in the CODEOWNERS
file.

For more information about the correct CODEOWNERS syntax,
see "[About code owners](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | query | string | No | A branch, tag or commit name used to determine which version of the CODEOWNERS file to use. Default: the repository's default branch (e.g. `main`) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | Resource not found |

**Success Response Schema:**

[codeowners-errors](../schemas/codeowners-errors/codeowners-errors.md)

