# projects

Endpoints to manage Projects using the REST API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/projectsV2` | List projects for organization | [View](../operations/projects-list-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}` | Get project for organization | [View](../operations/projects-get-for-org.md) |
| POST | `/orgs/{org}/projectsV2/{project_number}/drafts` | Create draft item for organization owned project | [View](../operations/projects-create-draft-item-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}/fields` | List project fields for organization | [View](../operations/projects-list-fields-for-org.md) |
| POST | `/orgs/{org}/projectsV2/{project_number}/fields` | Add a field to an organization-owned project. | [View](../operations/projects-add-field-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}/fields/{field_id}` | Get project field for organization | [View](../operations/projects-get-field-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}/items` | List items for an organization owned project | [View](../operations/projects-list-items-for-org.md) |
| POST | `/orgs/{org}/projectsV2/{project_number}/items` | Add item to organization owned project | [View](../operations/projects-add-item-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}/items/{item_id}` | Get an item for an organization owned project | [View](../operations/projects-get-org-item.md) |
| DELETE | `/orgs/{org}/projectsV2/{project_number}/items/{item_id}` | Delete project item for organization | [View](../operations/projects-delete-item-for-org.md) |
| PATCH | `/orgs/{org}/projectsV2/{project_number}/items/{item_id}` | Update project item for organization | [View](../operations/projects-update-item-for-org.md) |
| POST | `/orgs/{org}/projectsV2/{project_number}/views` | Create a view for an organization-owned project | [View](../operations/projects-create-view-for-org.md) |
| GET | `/orgs/{org}/projectsV2/{project_number}/views/{view_number}/items` | List items for an organization project view | [View](../operations/projects-list-view-items-for-org.md) |
| POST | `/user/{user_id}/projectsV2/{project_number}/drafts` | Create draft item for user owned project | [View](../operations/projects-create-draft-item-for-authenticated-user.md) |
| POST | `/users/{user_id}/projectsV2/{project_number}/views` | Create a view for a user-owned project | [View](../operations/projects-create-view-for-user.md) |
| GET | `/users/{username}/projectsV2` | List projects for user | [View](../operations/projects-list-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}` | Get project for user | [View](../operations/projects-get-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}/fields` | List project fields for user | [View](../operations/projects-list-fields-for-user.md) |
| POST | `/users/{username}/projectsV2/{project_number}/fields` | Add field to user owned project | [View](../operations/projects-add-field-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}/fields/{field_id}` | Get project field for user | [View](../operations/projects-get-field-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}/items` | List items for a user owned project | [View](../operations/projects-list-items-for-user.md) |
| POST | `/users/{username}/projectsV2/{project_number}/items` | Add item to user owned project | [View](../operations/projects-add-item-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}/items/{item_id}` | Get an item for a user owned project | [View](../operations/projects-get-user-item.md) |
| DELETE | `/users/{username}/projectsV2/{project_number}/items/{item_id}` | Delete project item for user | [View](../operations/projects-delete-item-for-user.md) |
| PATCH | `/users/{username}/projectsV2/{project_number}/items/{item_id}` | Update project item for user | [View](../operations/projects-update-item-for-user.md) |
| GET | `/users/{username}/projectsV2/{project_number}/views/{view_number}/items` | List items for a user project view | [View](../operations/projects-list-view-items-for-user.md) |
