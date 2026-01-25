# POST /rest/api/3/jql/pdcleaner

**Resource:** [JQL](../resources/JQL.md)
**Convert user identifiers to account IDs in JQL queries**
**Operation ID:** `migrateQueries`

Converts one or more JQL queries with user identifiers (username or user key) to equivalent JQL queries with account IDs.

You may wish to use this operation if your system stores JQL queries and you want to make them GDPR-compliant. For more information about GDPR-related changes, see the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/).

**[Permissions](#permissions) required:** Permission to access Jira.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JQLPersonalDataMigrationRequest](../schemas/JQLPersonalDataMigrationRequest/JQLPersonalDataMigrationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. Note that the JQL queries are returned in the same order that they were passed. |
| 400 | Returned if at least one of the queries cannot be converted. For example, the JQL has invalid operators or invalid keywords, or the users in the query cannot be found. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[ConvertedJQLQueries](../schemas/Converted/ConvertedJQLQueries.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
