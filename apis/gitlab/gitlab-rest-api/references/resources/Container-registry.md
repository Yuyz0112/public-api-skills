# Container registry

Operations related to container registry.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/registry/repositories` | List container repositories within a project | [View](../operations/getApiV4ProjectsIdRegistryRepositories.md) |
| DELETE | `/api/v4/projects/{id}/registry/repositories/{repository_id}` | Delete repository | [View](../operations/deleteApiV4ProjectsIdRegistryRepositoriesRepositoryId.md) |
| GET | `/api/v4/projects/{id}/registry/repositories/{repository_id}/tags` | List tags of a repository | [View](../operations/getApiV4ProjectsIdRegistryRepositoriesRepositoryIdTags.md) |
| DELETE | `/api/v4/projects/{id}/registry/repositories/{repository_id}/tags` | Delete repository tags (in bulk) | [View](../operations/deleteApiV4ProjectsIdRegistryRepositoriesRepositoryIdTags.md) |
| GET | `/api/v4/projects/{id}/registry/repositories/{repository_id}/tags/{tag_name}` | Get details about a repository tag | [View](../operations/getApiV4ProjectsIdRegistryRepositoriesRepositoryIdTagsTagName.md) |
| DELETE | `/api/v4/projects/{id}/registry/repositories/{repository_id}/tags/{tag_name}` | Delete repository tag | [View](../operations/deleteApiV4ProjectsIdRegistryRepositoriesRepositoryIdTagsTagName.md) |
| GET | `/api/v4/groups/{id}/registry/repositories` | List registry repositories within a group | [View](../operations/getApiV4GroupsIdRegistryRepositories.md) |
| GET | `/api/v4/registry/repositories/{id}` | Get a container repository | [View](../operations/getApiV4RegistryRepositoriesId.md) |
| POST | `/api/v4/container_registry_event/events` | Receives notifications from the container registry when an operation occurs | [View](../operations/postApiV4ContainerRegistryEventEvents.md) |
