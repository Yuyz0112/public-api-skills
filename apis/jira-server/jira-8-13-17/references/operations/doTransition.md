# POST /issue/{issueIdOrKey}/transitions

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `doTransition`

Perform a transition on an issue.
 When performing the transition you can update or set other issue fields.
 <p/>
 The fields that can be set on transtion, in either the fields parameter or the update parameter can be determined
 using the <b>/rest/api/2/issue/{issueIdOrKey}/transitions?expand=transitions.fields</b> resource.
 If a field is not configured to appear on the transition screen, then it will not be in the transition metadata, and a field
 validation error will occur if it is submitted.

 The <code>updateHistory</code> param adds the issues retrieved by this method to the current user's issue history,
 if set to true (by default, the issue history does not include issues retrieved via the REST API).
 You can view the issue history in the Jira application, via the Issues dropdown or by using the
 <code>lastViewed</code> JQL field in an issue search.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

