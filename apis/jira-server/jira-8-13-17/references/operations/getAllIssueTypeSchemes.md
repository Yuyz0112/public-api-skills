# GET /issuetypescheme

**Resource:** [issuetypescheme](../resources/issuetypescheme.md)
**Operation ID:** `getAllIssueTypeSchemes`

Returns a list of all issue type schemes visible to the user (must be admin).
 <p>
     All issue types associated with the scheme will only be returned if an additional query parameter is provided:
     <code>expand=schemes.issueTypes</code>.
 </p>
 <p>
     Similarly, the default issue type associated with the scheme (if one exists) will only be returned if
     additional an query parameter is provided: <code>expand=schemes.defaultIssueType</code>.
 </p>
 <p>
     Note that both query parameters can be used together: <code>expand=schemes.issueTypes,schemes.defaultIssueType</code>.
 </p>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

