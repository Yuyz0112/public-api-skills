# POST /rest/api/3/jql/sanitize

**Resource:** [JQL](../resources/JQL.md)
**Sanitize JQL queries**
**Operation ID:** `sanitiseJqlQueries`

Sanitizes one or more JQL queries by converting readable details into IDs where a user doesn't have permission to view the entity.

For example, if the query contains the clause *project = 'Secret project'*, and a user does not have browse permission for the project "Secret project", the sanitized query replaces the clause with *project = 12345"* (where 12345 is the ID of the project). If a user has the required permission, the clause is not sanitized. If the account ID is null, sanitizing is performed for an anonymous user.

Note that sanitization doesn't make the queries GDPR-compliant, because it doesn't remove user identifiers (username or user key). If you need to make queries GDPR-compliant, use [Convert user identifiers to account IDs in JQL queries](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jql/#api-rest-api-3-jql-sanitize-post).

Before sanitization each JQL query is parsed. The queries are returned in the same order that they were passed.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JqlQueriesToSanitize](../schemas/Jql/JqlQueriesToSanitize.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[SanitizedJqlQueries](../schemas/Sanitized/SanitizedJqlQueries.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
