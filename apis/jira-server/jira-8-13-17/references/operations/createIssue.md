# POST /issue

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `createIssue`

Creates an issue or a sub-task from a JSON representation.
 <p/>
 The fields that can be set on create, in either the fields parameter or the update parameter can be determined
 using the <b>/rest/api/2/issue/createmeta</b> resource.
 If a field is not configured to appear on the create screen, then it will not be in the createmeta, and a field
 validation error will occur if it is submitted.
 <p/>
 Creating a sub-task is similar to creating a regular issue, with two important differences:
 <ul>
 <li>the <code>issueType</code> field must correspond to a sub-task issue type (you can use
 <code>/issue/createmeta</code> to discover sub-task issue types), and</li>
 <li>you must provide a <code>parent</code> field in the issue create request containing the id or key of the
 parent issue.</li>
 <li>The <code>updateHistory</code> param adds the project that this issue is created in, to the current user's project history,
 if set to true (by default, the project history is not updated).</li>
 <li>You can view the project history in the Jira application, via the Projects dropdown.</li>
 </ul>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `updateHistory` | query | boolean | No | if true then the user's project history is updated |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

