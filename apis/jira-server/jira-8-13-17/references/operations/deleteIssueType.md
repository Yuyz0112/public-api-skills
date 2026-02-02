# DELETE /issuetype/{id}

**Resource:** [issuetype](../resources/issuetype.md)
**Operation ID:** `deleteIssueType`

Deletes the specified issue type. If the issue type has any associated issues, these issues will be migrated to
 the alternative issue type specified in the parameter. You can determine the alternative issue types by calling
 the <b>/rest/api/2/issuetype/{id}/alternatives</b> resource.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `alternativeIssueTypeId` | query | string | No | the id of an issue type to which issues associated with the removed issue type will be migrated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

