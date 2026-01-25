# GET /orgs/{org}/properties/schema

**Resource:** [orgs](../resources/orgs.md)
**Get all custom properties for an organization**
**Operation ID:** `orgs/custom-properties-for-repos-get-organization-definitions`

Gets all custom properties defined for an organization.
Organization members can read these properties.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [custom-property](../schemas/custom-property/custom-property.md)

