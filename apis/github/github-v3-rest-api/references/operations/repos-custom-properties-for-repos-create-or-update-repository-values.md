# PATCH /repos/{owner}/{repo}/properties/values

**Resource:** [repos](../resources/repos.md)
**Create or update custom property values for a repository**
**Operation ID:** `repos/custom-properties-for-repos-create-or-update-repository-values`

Create new or update existing custom property values for a repository.
Using a value of `null` for a custom property will remove or 'unset' the property value from the repository.

Repository admins and other users with the repository-level "edit custom property values" fine-grained permission can use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content when custom property values are successfully created or updated |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

