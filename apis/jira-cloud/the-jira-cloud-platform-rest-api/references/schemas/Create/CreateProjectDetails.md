# CreateProjectDetails

Details about the project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assigneeType` | enum: PROJECT_LEAD, UNASSIGNED | No | The default assignee when creating issues for this project. |
| `avatarId` | integer (int64) | No | An integer value for the project's avatar. |
| `categoryId` | integer (int64) | No | The ID of the project's category. A complete list of category IDs is found using the [Get all project categories](#api-rest-api-3-projectCategory-get) operation. |
| `description` | string | No | A brief description of the project. |
| `fieldConfigurationScheme` | integer (int64) | No | The ID of the field configuration scheme for the project. Use the [Get all field configuration schemes](#api-rest-api-3-fieldconfigurationscheme-get) operation to get a list of field configuration scheme IDs. If you specify the field configuration scheme you cannot specify the project template key. |
| `issueSecurityScheme` | integer (int64) | No | The ID of the issue security scheme for the project, which enables you to control who can and cannot view issues. Use the [Get issue security schemes](#api-rest-api-3-issuesecurityschemes-get) resource to get all issue security scheme IDs. |
| `issueTypeScheme` | integer (int64) | No | The ID of the issue type scheme for the project. Use the [Get all issue type schemes](#api-rest-api-3-issuetypescheme-get) operation to get a list of issue type scheme IDs. If you specify the issue type scheme you cannot specify the project template key. |
| `issueTypeScreenScheme` | integer (int64) | No | The ID of the issue type screen scheme for the project. Use the [Get all issue type screen schemes](#api-rest-api-3-issuetypescreenscheme-get) operation to get a list of issue type screen scheme IDs. If you specify the issue type screen scheme you cannot specify the project template key. |
| `key` | string | Yes | Project keys must be unique and start with an uppercase letter followed by one or more uppercase alphanumeric characters. The maximum length is 10 characters. |
| `lead` | string | No | This parameter is deprecated because of privacy changes. Use `leadAccountId` instead. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. The user name of the project lead. Either `lead` or `leadAccountId` must be set when creating a project. Cannot be provided with `leadAccountId`. |
| `leadAccountId` | string | No | The account ID of the project lead. Either `lead` or `leadAccountId` must be set when creating a project. Cannot be provided with `lead`. |
| `name` | string | Yes | The name of the project. |
| `notificationScheme` | integer (int64) | No | The ID of the notification scheme for the project. Use the [Get notification schemes](#api-rest-api-3-notificationscheme-get) resource to get a list of notification scheme IDs. |
| `permissionScheme` | integer (int64) | No | The ID of the permission scheme for the project. Use the [Get all permission schemes](#api-rest-api-3-permissionscheme-get) resource to see a list of all permission scheme IDs. |
| `projectTemplateKey` | enum: com.pyxis.greenhopper.jira:gh-simplified-agility-kanban, com.pyxis.greenhopper.jira:gh-simplified-agility-scrum, com.pyxis.greenhopper.jira:gh-simplified-basic... | No | A predefined configuration for a project. The type of the `projectTemplateKey` must match with the type of the `projectTypeKey`. |
| `projectTypeKey` | enum: software, service_desk, business | No | The [project type](https://confluence.atlassian.com/x/GwiiLQ#Jiraapplicationsoverview-Productfeaturesandprojecttypes), which defines the application-specific feature set. If you don't specify the project template you have to specify the project type. |
| `url` | string | No | A link to information about this project, such as project documentation |
| `workflowScheme` | integer (int64) | No | The ID of the workflow scheme for the project. Use the [Get all workflow schemes](#api-rest-api-3-workflowscheme-get) operation to get a list of workflow scheme IDs. If you specify the workflow scheme you cannot specify the project template key. |

