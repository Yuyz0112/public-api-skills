# PATCH /orgs/{org}/properties/values

**Resource:** [orgs](../resources/orgs.md)
**Create or update custom property values for organization repositories**
**Operation ID:** `orgs/custom-properties-for-repos-create-or-update-organization-values`

Create new or update existing custom property values for repositories in a batch that belong to an organization.
Each target repository will have its custom property values updated to match the values provided in the request.

A maximum of 30 repositories can be updated in a single request.

Using a value of `null` for a custom property will remove or 'unset' the property value from the repository.

To use this endpoint, the authenticated user must be one of:
  - An administrator for the organization.
  - A user, or a user on a team, with the fine-grained permission of `custom_properties_org_values_editor` in the organization.

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

