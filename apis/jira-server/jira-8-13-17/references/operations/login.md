# POST /session

**Resource:** [session](../resources/session.md)
**Operation ID:** `login`

Creates a new session for a user in Jira. Once a session has been successfully created it can be used to access
 any of Jira's remote APIs and also the web UI by passing the appropriate HTTP Cookie header.
 <p>
 Note that it is generally preferrable to use HTTP BASIC authentication with the REST API. However, this resource
 may be used to mimic the behaviour of Jira's log-in page (e.g. to display log-in errors to a user).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

