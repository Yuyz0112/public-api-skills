# GET /orgs/{org}/properties/schema/{custom_property_name}

**Resource:** [orgs](../resources/orgs.md)
**Get a custom property for an organization**
**Operation ID:** `orgs/custom-properties-for-repos-get-organization-definition`

Gets a custom property that is defined for an organization.
Organization members can read these properties.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[custom-property](../schemas/custom-property/custom-property.md)

