# Project

Details about a project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archived` | boolean | No | Whether the project is archived. |
| `archivedBy` | any | No | The user who archived the project. |
| `archivedDate` | string (date-time) | No | The date when the project was archived. |
| `assigneeType` | enum: PROJECT_LEAD, UNASSIGNED | No | The default assignee when creating issues for this project. |
| `avatarUrls` | any | No | The URLs of the project's avatars. |
| `components` | ProjectComponent[] | No | List of the components contained in the project. |
| `deleted` | boolean | No | Whether the project is marked as deleted. |
| `deletedBy` | any | No | The user who marked the project as deleted. |
| `deletedDate` | string (date-time) | No | The date when the project was marked as deleted. |
| `description` | string | No | A brief description of the project. |
| `email` | string | No | An email address associated with the project. |
| `expand` | string | No | Expand options that include additional project details in the response. |
| `favourite` | boolean | No | Whether the project is selected as a favorite. |
| `id` | string | No | The ID of the project. |
| `insight` | any | No | Insights about the project. |
| `isPrivate` | boolean | No | Whether the project is private from the user's perspective. This means the user can't see the project or any associated issues. |
| `issueTypeHierarchy` | any | No | The issue type hierarchy for the project. |
| `issueTypes` | IssueTypeDetails[] | No | List of the issue types available in the project. |
| `key` | string | No | The key of the project. |
| `landingPageInfo` | any | No | The project landing page info. |
| `lead` | any | No | The username of the project lead. |
| `name` | string | No | The name of the project. |
| `permissions` | any | No | User permissions on the project |
| `projectCategory` | any | No | The category the project belongs to. |
| `projectTypeKey` | enum: software, service_desk, business | No | The [project type](https://confluence.atlassian.com/x/GwiiLQ#Jiraapplicationsoverview-Productfeaturesandprojecttypes) of the project. |
| `properties` | object | No | Map of project properties |
| `retentionTillDate` | string (date-time) | No | The date when the project is deleted permanently. |
| `roles` | object | No | The name and self URL for each role defined in the project. For more information, see [Create project role](#api-rest-api-3-role-post). |
| `self` | string (uri) | No | The URL of the project details. |
| `simplified` | boolean | No | Whether the project is simplified. |
| `style` | enum: classic, next-gen | No | The type of the project. |
| `url` | string | No | A link to information about this project, such as project documentation. |
| `uuid` | string (uuid) | No | Unique ID for next-gen projects. |
| `versions` | Version[] | No | The versions defined in the project. For more information, see [Create version](#api-rest-api-3-version-post). |

