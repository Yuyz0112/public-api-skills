# PUT /rest/api/3/plans/plan/{planId}

**Resource:** [Plans](../resources/Plans.md)
**Update plan**
**Operation ID:** `updatePlan`

Updates any of the following details of a plan using [JSON Patch](https://datatracker.ietf.org/doc/html/rfc6902).

 *  name
 *  leadAccountId
 *  scheduling
    
     *  estimation with StoryPoints, Days or Hours as possible values
     *  startDate
        
         *  type with DueDate, TargetStartDate, TargetEndDate or DateCustomField as possible values
         *  dateCustomFieldId
     *  endDate
        
         *  type with DueDate, TargetStartDate, TargetEndDate or DateCustomField as possible values
         *  dateCustomFieldId
     *  inferredDates with None, SprintDates or ReleaseDates as possible values
     *  dependencies with Sequential or Concurrent as possible values
 *  issueSources
    
     *  type with Board, Project or Filter as possible values
     *  value
 *  exclusionRules
    
     *  numberOfDaysToShowCompletedIssues
     *  issueIds
     *  workStatusIds
     *  workStatusCategoryIds
     *  issueTypeIds
     *  releaseIds
 *  crossProjectReleases
    
     *  name
     *  releaseIds
 *  customFields
    
     *  customFieldId
     *  filter
 *  permissions
    
     *  type with View or Edit as possible values
     *  holder
        
         *  type with Group or AccountId as possible values
         *  value

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

*Note that "add" operations do not respect array indexes in target locations. Call the "Get plan" endpoint to find out the order of array elements.*

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `useGroupId` | query | boolean | No | Whether to accept group IDs instead of group names. Group names are deprecated. |

## Request Body

**Required:** Yes

**Content Types:** `application/json-patch+json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan is not found. |
| 409 | Returned if the plan is not active. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
