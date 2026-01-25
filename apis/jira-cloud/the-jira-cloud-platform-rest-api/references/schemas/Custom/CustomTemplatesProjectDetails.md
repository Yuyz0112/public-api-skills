# CustomTemplatesProjectDetails

Project Details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessLevel` | enum: open, limited, private... | No | The access level of the project. Only used by team-managed project |
| `additionalProperties` | object | No | Additional properties of the project |
| `assigneeType` | enum: PROJECT_DEFAULT, COMPONENT_LEAD, PROJECT_LEAD... | No | The default assignee when creating issues in the project |
| `avatarId` | integer (int64) | No | The ID of the project's avatar. Use the \[Get project avatars\](\#api-rest-api-3-project-projectIdOrKey-avatar-get) operation to list the available avatars in a project. |
| `categoryId` | integer (int64) | No | The ID of the project's category. A complete list of category IDs is found using the [Get all project categories](#api-rest-api-3-projectCategory-get) operation. |
| `description` | string | No | Brief description of the project |
| `enableComponents` | boolean | No | Whether components are enabled for the project. Only used by company-managed project |
| `key` | string | No | Project keys must be unique and start with an uppercase letter followed by one or more uppercase alphanumeric characters. The maximum length is 10 characters. |
| `language` | string | No | The default language for the project |
| `leadAccountId` | string | No | The account ID of the project lead. Either `lead` or `leadAccountId` must be set when creating a project. Cannot be provided with `lead`. |
| `name` | string | No | Name of the project |
| `url` | string | No | A link to information about this project, such as project documentation |

