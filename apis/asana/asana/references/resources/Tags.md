# Tags

A tag is a label that can be attached to any task in Asana. It exists in a single workspace or organization.

Tags have some metadata associated with them, but it is possible that we will simplify them in the future so it is not encouraged to rely too heavily on it. Unlike projects, tags do not provide any ordering on the tasks they are associated with.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/tags` | Get multiple tags | [View](../operations/getTags.md) |
| POST | `/tags` | Create a tag | [View](../operations/createTag.md) |
| GET | `/tags/{tag_gid}` | Get a tag | [View](../operations/getTag.md) |
| PUT | `/tags/{tag_gid}` | Update a tag | [View](../operations/updateTag.md) |
| DELETE | `/tags/{tag_gid}` | Delete a tag | [View](../operations/deleteTag.md) |
| GET | `/tasks/{task_gid}/tags` | Get a task's tags | [View](../operations/getTagsForTask.md) |
| GET | `/workspaces/{workspace_gid}/tags` | Get tags in a workspace | [View](../operations/getTagsForWorkspace.md) |
| POST | `/workspaces/{workspace_gid}/tags` | Create a tag in a workspace | [View](../operations/createTagForWorkspace.md) |
