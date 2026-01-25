# GET /repos/{owner}/{repo}/codespaces/permissions_check

**Resource:** [codespaces](../resources/codespaces.md)
**Check if permissions defined by a devcontainer have been accepted by the authenticated user**
**Operation ID:** `codespaces/check-permissions-for-devcontainer`

Checks whether the permissions defined by a given devcontainer configuration have been accepted by the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | query | string | Yes | The git reference that points to the location of the devcontainer configuration to use for the permission check. The value of `ref` will typically be a branch name (`heads/BRANCH_NAME`). For more information, see "[Git References](https://git-scm.com/book/en/v2/Git-Internals-Git-References)" in the Git documentation. |
| `devcontainer_path` | query | string | Yes | Path to the devcontainer.json configuration to use for the permission check. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response when the permission check is successful |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[codespaces-permissions-check-for-devcontainer](../schemas/codespaces-permissions-check-for-devcontainer/codespaces-permissions-check-for-devcontainer.md)

