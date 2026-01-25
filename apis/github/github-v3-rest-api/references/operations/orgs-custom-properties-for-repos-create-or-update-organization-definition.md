# PUT /orgs/{org}/properties/schema/{custom_property_name}

**Resource:** [orgs](../resources/orgs.md)
**Create or update a custom property for an organization**
**Operation ID:** `orgs/custom-properties-for-repos-create-or-update-organization-definition`

Creates a new or updates an existing custom property that is defined for an organization.

To use this endpoint, the authenticated user must be one of:
- An administrator for the organization.
- A user, or a user on a team, with the fine-grained permission of `custom_properties_org_definitions_manager` in the organization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [custom-property-set-payload](../schemas/custom-property-set-payload/custom-property-set-payload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[custom-property](../schemas/custom-property/custom-property.md)

