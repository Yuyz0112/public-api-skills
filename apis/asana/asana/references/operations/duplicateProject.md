# POST /projects/{project_gid}/duplicate

**Resource:** [Projects](../resources/Projects.md)
**Duplicate a project**
**Operation ID:** `duplicateProject`

<b>Required scope: </b><code>projects:write</code>

Creates and returns a job that will asynchronously handle the duplication.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Describes the duplicate's name and the elements that will be duplicated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the job to handle duplication. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write
