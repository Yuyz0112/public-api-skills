# POST /organization_exports

**Resource:** [Organization exports](../resources/Organization-exports.md)
**Create an organization export request**
**Operation ID:** `createOrganizationExport`

This method creates a request to export an Organization. Asana will complete the export at some point after you create the request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The organization to export.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created organization export request. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
