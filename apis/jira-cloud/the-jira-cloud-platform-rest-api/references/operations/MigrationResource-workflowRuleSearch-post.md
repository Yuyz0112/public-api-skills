# POST /rest/atlassian-connect/1/migration/workflow/rule/search

**Resource:** [App migration](../resources/App-migration.md)
**Get workflow transition rule configurations**
**Operation ID:** `MigrationResource.workflowRuleSearch_post`

Returns configurations for workflow transition rules migrated from server to cloud and owned by the calling Connect app.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Atlassian-Transfer-Id` | header | string (uuid) | Yes | The app migration transfer ID. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowRulesSearch](../schemas/Workflow/WorkflowRulesSearch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 403 | Returned if the authorisation credentials are incorrect or missing. |

**Success Response Schema:**

[WorkflowRulesSearchDetails](../schemas/Workflow/WorkflowRulesSearchDetails.md)

