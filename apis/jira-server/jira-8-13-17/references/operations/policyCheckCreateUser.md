# POST /password/policy/createUser

**Resource:** [password](../resources/password.md)
**Operation ID:** `policyCheckCreateUser`

Returns a list of statements explaining why the password policy would disallow a proposed password for a new user.
 <p>
 You can use this method to test the password policy validation. This could be done prior to an action 
 where a new user and related password are created, using methods like the ones in 
 <a href="https://docs.atlassian.com/jira/latest/com/atlassian/jira/bc/user/UserService.html">UserService</a>.      
 For example, you could use this to validate a password in a create user form in the user interface, as the user enters it.<br/>
 The username and new password must be not empty to perform the validation.<br/>
 Note, this method will help you validate against the policy only. It won't check any other validations that might be performed 
 when creating a new user, e.g. checking whether a user with the same name already exists.
 </p>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

