# GET /users/{username}/packages

**Resource:** [packages](../resources/packages.md)
**List packages for a user**
**Operation ID:** `packages/list-packages-for-user`

Lists all packages in a user's namespace for which the requesting user has access.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint. For more information, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#permissions-for-repository-scoped-packages)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_type` | query | enum: npm, maven, rubygems... | Yes | The type of supported package. Packages in GitHub's Gradle registry have the type `maven`. Docker images pushed to GitHub's Container registry (`ghcr.io`) have the type `container`. You can use the type `docker` to find images that were pushed to GitHub's Docker registry (`docker.pkg.github.com`), even if these have now been migrated to the Container registry. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [package](../schemas/package/package.md)

