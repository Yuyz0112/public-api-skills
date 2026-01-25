# IssueTypeProjectCreatePayload

The payload for creating issue types in a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueTypeHierarchy` | IssueTypeHierarchyPayload[] | No | Defines the issue type hierarhy to be created and used during this project creation. This will only add new levels if there isn't an existing level |
| `issueTypeScheme` | [IssueTypeSchemePayload](IssueTypeSchemePayload.md) | No |  |
| `issueTypes` | IssueTypePayload[] | No | Only needed if you want to create issue types, you can otherwise use the ids of issue types in the scheme configuration |

