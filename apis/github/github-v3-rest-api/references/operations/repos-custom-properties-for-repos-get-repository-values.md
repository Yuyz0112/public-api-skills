# GET /repos/{owner}/{repo}/properties/values

**Resource:** [repos](../resources/repos.md)
**Get all custom property values for a repository**
**Operation ID:** `repos/custom-properties-for-repos-get-repository-values`

Gets all custom property values that are set for a repository.
Users with read access to the repository can use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [custom-property-value](../schemas/custom-property-value/custom-property-value.md)

