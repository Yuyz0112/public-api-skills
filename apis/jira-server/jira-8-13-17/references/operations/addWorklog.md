# POST /issue/{issueIdOrKey}/worklog

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `addWorklog`

Adds a new worklog entry to an issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `adjustEstimate` | query | string | No | (optional) allows you to provide specific instructions to update the remaining time estimate of the issue.  Valid values are
                       <ul>
                       <li>"new" - sets the estimate to a specific value</li>
                       <li>"leave"- leaves the estimate as is</li>
                       <li>"manual" - specify a specific amount to increase remaining estimate by</li>
                       <li>"auto"- Default option.  Will automatically adjust the value based on the new timeSpent specified on the worklog</li> </ul> |
| `newEstimate` | query | string | No | (required when "new" is selected for adjustEstimate) the new value for the remaining estimate field. e.g. "2d" |
| `reduceBy` | query | string | No | (required when "manual" is selected for adjustEstimate) the amount to reduce the remaining estimate by e.g. "2d" |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

