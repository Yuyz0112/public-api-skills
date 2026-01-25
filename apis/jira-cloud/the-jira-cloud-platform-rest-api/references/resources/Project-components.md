# Project components

This resource represents project components. Use it to get, create, update, and delete project components. Also get components for project and get a count of issues by component.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/component` | Find components for projects | [View](../operations/findComponentsForProjects.md) |
| POST | `/rest/api/3/component` | Create component | [View](../operations/createComponent.md) |
| GET | `/rest/api/3/component/{id}` | Get component | [View](../operations/getComponent.md) |
| PUT | `/rest/api/3/component/{id}` | Update component | [View](../operations/updateComponent.md) |
| DELETE | `/rest/api/3/component/{id}` | Delete component | [View](../operations/deleteComponent.md) |
| GET | `/rest/api/3/component/{id}/relatedIssueCounts` | Get component issues count | [View](../operations/getComponentRelatedIssues.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}/component` | Get project components paginated | [View](../operations/getProjectComponentsPaginated.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}/components` | Get project components | [View](../operations/getProjectComponents.md) |
