# PATCH /orgs/{org}/properties/schema

**Resource:** [orgs](../resources/orgs.md)
**Create or update custom properties for an organization**
**Operation ID:** `orgs/custom-properties-for-repos-create-or-update-organization-definitions`

Creates new or updates existing custom properties defined for an organization in a batch.

If the property already exists, the existing property will be replaced with the new values.
Missing optional values will fall back to default values, previous values will be overwritten.
E.g. if a property exists with `values_editable_by: org_and_repo_actors` and it's updated without specifying `values_editable_by`, it will be updated to default value `org_actors`.

To use this endpoint, the authenticated user must be one of:
  - An administrator for the organization.
  - A user, or a user on a team, with the fine-grained permission of `custom_properties_org_definitions_manager` in the organization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [custom-property](../schemas/custom-property/custom-property.md)

