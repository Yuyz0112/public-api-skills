# POST /projects/{project_gid}/project_statuses

**Resource:** [Project statuses](../resources/Project-statuses.md)
**Create a project status**
**Operation ID:** `createProjectStatusForProject`

*Deprecated: new integrations should prefer the `/status_updates` route.*

Creates a new status update on the project.

Returns the full record of the newly created project status update.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The project status to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a new story. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
