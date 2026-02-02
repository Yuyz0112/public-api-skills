# POST /password/policy/updateUser

**Resource:** [password](../resources/password.md)
**Operation ID:** `policyCheckUpdateUser`

Returns a list of statements explaining why the password policy would disallow a proposed new password for a user with an existing password.
 <p>
 You can use this method to test the password policy validation. This could be done prior to an action where the password 
 is actually updated, using methods like <a href="https://docs.atlassian.com/jira/latest/com/atlassian/jira/web/action/user/ChangePassword.html">ChangePassword</a>      
 or <a href="https://docs.atlassian.com/jira/latest/com/atlassian/jira/web/action/user/ResetPassword.html">ResetPassword</a>. 
 For example, you could use this to validate a password in a change password form in the user interface, as the user enters it.<br/>
 The user must exist and the username and new password must be not empty, to perform the validation.<br/>
 Note, this method will help you validate against the policy only. It won't check any other validations that might be performed 
 when submitting a password change/reset request, e.g. verifying whether the old password is valid.
 </p>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

