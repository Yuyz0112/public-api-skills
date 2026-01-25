# Project briefs

A project brief object represents a rich text document that describes a project.

Please note that this API is in *preview*, and is expected to change. This API is to be used for development and testing only as an advance view into the upcoming rich text format experience in the task description. For more information, see [this post](https://forum.asana.com/t/project-brief-api-now-available-as-a-preview/150885) in the developer forum.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/project_briefs/{project_brief_gid}` | Get a project brief | [View](../operations/getProjectBrief.md) |
| PUT | `/project_briefs/{project_brief_gid}` | Update a project brief | [View](../operations/updateProjectBrief.md) |
| DELETE | `/project_briefs/{project_brief_gid}` | Delete a project brief | [View](../operations/deleteProjectBrief.md) |
| POST | `/projects/{project_gid}/project_briefs` | Create a project brief | [View](../operations/createProjectBrief.md) |
