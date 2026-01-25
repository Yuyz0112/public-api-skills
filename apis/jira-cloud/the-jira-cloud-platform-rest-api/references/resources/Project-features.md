# Project features

This resource represents project features. Use it to get the list of features for a project and modify the state of a feature. The project feature endpoint is available only for Jira Software, both for team- and company-managed projects.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/project/{projectIdOrKey}/features` | Get project features | [View](../operations/getFeaturesForProject.md) |
| PUT | `/rest/api/3/project/{projectIdOrKey}/features/{featureKey}` | Set project feature state | [View](../operations/toggleFeatureForProject.md) |
