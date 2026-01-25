# POST /repos/{owner}/{repo}/branches/{branch}/rename

**Resource:** [repos](../resources/repos.md)
**Rename a branch**
**Operation ID:** `repos/rename-branch`

Renames a branch in a repository.

> [!NOTE]
> Although the API responds immediately, the branch rename process might take some extra time to complete in the background. You won't be able to push to the old branch name while the rename process is in progress. For more information, see "[Renaming a branch](https://docs.github.com/github/administering-a-repository/renaming-a-branch)".

The authenticated user must have push access to the branch. If the branch is the default branch, the authenticated user must also have admin or owner permissions.

In order to rename the default branch, fine-grained access tokens also need the `administration:write` repository permission.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[branch-with-protection](../schemas/branch-with-protection/branch-with-protection.md)

