# PrioritySchemeWithPaginatedPrioritiesAndProjects

A priority scheme with paginated priorities and projects.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | boolean | No |  |
| `defaultPriorityId` | string | No | The ID of the default issue priority. |
| `description` | string | No | The description of the priority scheme |
| `id` | string | Yes | The ID of the priority scheme. |
| `isDefault` | boolean | No |  |
| `name` | string | Yes | The name of the priority scheme |
| `priorities` | any | No | The paginated list of priorities. |
| `projects` | any | No | The paginated list of projects. |
| `self` | string | No | The URL of the priority scheme. |

