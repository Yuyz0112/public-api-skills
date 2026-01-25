# POST /rest/api/3/project-template

**Resource:** [Project templates](../resources/Project-templates.md)
**Create custom project**
**Operation ID:** `createProjectWithCustomTemplate`

Creates a project based on a custom template provided in the request.

The request body should contain the project details and the capabilities that comprise the project:

 *  `details` \- represents the project details settings
 *  `template` \- represents a list of capabilities responsible for creating specific parts of a project

A capability is defined as a unit of configuration for the project you want to create.

This operation is:

 *  [asynchronous](#async). Follow the `Location` link in the response header to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

***Note: This API is only supported for Jira Enterprise edition.***

## Request Body

The JSON payload containing the project details and capabilities

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectCustomTemplateCreateRequestDTO](../schemas/Project/ProjectCustomTemplateCreateRequestDTO.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | The project creation task has been queued for execution |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
