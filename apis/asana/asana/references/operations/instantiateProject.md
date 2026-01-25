# POST /project_templates/{project_template_gid}/instantiateProject

**Resource:** [Project templates](../resources/Project-templates.md)
**Instantiate a project from a project template**
**Operation ID:** `instantiateProject`

<b>Required scope: </b><code>projects:write</code>

Creates and returns a job that will asynchronously handle the project instantiation.

To form this request, it is recommended to first make a request to [get a project template](/reference/getprojecttemplate). Then, from the response, copy the `gid` from the object in the `requested_dates` array. This `gid` should be used in `requested_dates` to instantiate a project.

_Note: The body of this request will differ if your workspace is an organization. To determine if your workspace is an organization, use the [is_organization](/reference/workspaces) parameter._

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Describes the inputs used for instantiating a project, such as the resulting project's name, which team it should be created in, and values for date variables.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the job to handle project instantiation. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write
