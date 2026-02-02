# GET /issuetype/{id}/alternatives

**Resource:** [issuetype](../resources/issuetype.md)
**Operation ID:** `getAlternativeIssueTypes`

Returns a list of all alternative issue types for the given issue type id. The list will contain these issues types, to which
 issues assigned to the given issue type can be migrated. The suitable alternatives are issue types which are assigned
 to the same workflow, the same field configuration and the same screen scheme.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

