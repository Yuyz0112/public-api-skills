# POST /task_templates/{task_template_gid}/instantiateTask

**Resource:** [Task templates](../resources/Task-templates.md)
**Instantiate a task from a task template**
**Operation ID:** `instantiateTask`

Creates and returns a job that will asynchronously handle the task instantiation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Describes the inputs used for instantiating a task - the task's name.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the job to handle task instantiation. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
