# UiModificationContextDetails

The details of a UI modification's context, which define where to activate the UI modification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the UI modification context. |
| `isAvailable` | boolean | No | Whether a context is available. For example, when a project is deleted the context becomes unavailable. |
| `issueTypeId` | string | No | The issue type ID of the context. Null is treated as a wildcard, meaning the UI modification will be applied to all issue types. Each UI modification context can have a maximum of one wildcard. |
| `portalId` | string | No | The portal ID of the context. Only required for Jira Service Management request create portal view (`JSMRequestCreate`). |
| `projectId` | string | No | The project ID of the context. Null is treated as a wildcard, meaning the UI modification will be applied to all projects. Each UI modification context can have a maximum of one wildcard. |
| `requestTypeId` | string | No | The request type ID of the context. Only required for Jira Service Management request create portal view (`JSMRequestCreate`). |
| `viewType` | enum: GIC, IssueView, IssueTransition... | No | The view type of the context.  
Supported values:

 *  `GIC` \- Jira global issue create
 *  `IssueView` \- Jira issue view
 *  `IssueTransition` \- Jira issue transition
 *  `JSMRequestCreate` \- Jira Service Management request create portal view

For Jira view types (`GIC`, `IssueView`, `IssueTransition`), null is treated as a wildcard, meaning the UI modification will be applied to all view types. Each Jira context can have a maximum of one wildcard.  
  
Wildcards are not applicable for JSM contexts. |

