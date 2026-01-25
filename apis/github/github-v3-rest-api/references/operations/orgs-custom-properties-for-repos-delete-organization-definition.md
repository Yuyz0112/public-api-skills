# DELETE /orgs/{org}/properties/schema/{custom_property_name}

**Resource:** [orgs](../resources/orgs.md)
**Remove a custom property for an organization**
**Operation ID:** `orgs/custom-properties-for-repos-delete-organization-definition`

Removes a custom property that is defined for an organization.

To use this endpoint, the authenticated user must be one of:
  - An administrator for the organization.
  - A user, or a user on a team, with the fine-grained permission of `custom_properties_org_definitions_manager` in the organization.

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

