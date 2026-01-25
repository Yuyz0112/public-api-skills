# Workflow transition properties

This resource represents workflow transition properties, which provides for storing custom data against a workflow transition. Use it to get, create, and delete workflow transition properties as well as get a list of property keys for a workflow transition. Workflow transition properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/workflow/transitions/{transitionId}/properties` | Get workflow transition properties | [View](../operations/getWorkflowTransitionProperties.md) |
| PUT | `/rest/api/3/workflow/transitions/{transitionId}/properties` | Update workflow transition property | [View](../operations/updateWorkflowTransitionProperty.md) |
| POST | `/rest/api/3/workflow/transitions/{transitionId}/properties` | Create workflow transition property | [View](../operations/createWorkflowTransitionProperty.md) |
| DELETE | `/rest/api/3/workflow/transitions/{transitionId}/properties` | Delete workflow transition property | [View](../operations/deleteWorkflowTransitionProperty.md) |
