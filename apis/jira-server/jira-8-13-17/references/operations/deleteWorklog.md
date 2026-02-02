# DELETE /issue/{issueIdOrKey}/worklog/{id}

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `deleteWorklog`

Deletes an existing worklog entry.

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
| `increaseBy` | query | string | No | (required when "manual" is selected for adjustEstimate) the amount to increase the remaining estimate by e.g. "2d" |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

