# PUT /issue/{issueIdOrKey}

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `editIssue`

Edits an issue from a JSON representation.
 <p/>
 The issue can either be updated by setting explicit the field value(s)
 or by using an operation to change the field value.
 <p/>
 The fields that can be updated, in either the fields parameter or the update parameter, can be determined
 using the <b>/rest/api/2/issue/{issueIdOrKey}/editmeta</b> resource.<br>
 If a field is not configured to appear on the edit screen, then it will not be in the editmeta, and a field
 validation error will occur if it is submitted.
 <p/>
 Specifying a "field_id": field_value in the "fields" is a shorthand for a "set" operation in the "update" section.<br>
 Field should appear either in "fields" or "update", not in both.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `notifyUsers` | query | boolean | No | send the email with notification that the issue was updated to users that watch it.
                     Admin or project admin permissions are required to disable the notification. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

