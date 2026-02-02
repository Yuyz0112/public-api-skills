# PUT /issue/{issueIdOrKey}/worklog/{id}

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `updateWorklog`

Updates an existing worklog entry.
 <p>Note that:</p>
 <ul>
     <li>Fields possible for editing are: comment, visibility, started, timeSpent and timeSpentSeconds.</li>
     <li>Either timeSpent or timeSpentSeconds can be set.</li>
     <li>Fields which are not set will not be updated.</li>
     <li>For a request to be valid, it has to have at least one field change.</li>
 </ul>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `adjustEstimate` | query | string | No | (optional) allows you to provide specific instructions to update the remaining time estimate of the issue.  Valid values are
                       <ul>
                       <li>"new" - sets the estimate to a specific value</li>
                       <li>"leave"- leaves the estimate as is</li>
                       <li>"auto"- Default option.  Will automatically adjust the value based on the new timeSpent specified on the worklog</li> </ul> |
| `newEstimate` | query | string | No | (required when "new" is selected for adjustEstimate) the new value for the remaining estimate field. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

