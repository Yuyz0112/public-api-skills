# POST /projects/{project_gid}/saveAsTemplate

**Resource:** [Projects](../resources/Projects.md)
**Create a project template from a project**
**Operation ID:** `projectSaveAsTemplate`

Creates and returns a job that will asynchronously handle the project template creation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Describes the inputs used for creating a project template, such as the resulting project template's name, which team it should be created in.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the job to handle project template creation. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
