# POST /rest/api/3/jql/parse

**Resource:** [JQL](../resources/JQL.md)
**Parse JQL query**
**Operation ID:** `parseJqlQueries`

Parses and validates JQL queries.

Validation is performed in context of the current user.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `validation` | query | enum: strict, warn, none | Yes | How to validate the JQL query and treat the validation results. Validation options include:

 *  `strict` Returns all errors. If validation fails, the query structure is not returned.
 *  `warn` Returns all errors. If validation fails but the JQL query is correctly formed, the query structure is returned.
 *  `none` No validation is performed. If JQL query is correctly formed, the query structure is returned. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JqlQueriesToParse](../schemas/Jql/JqlQueriesToParse.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[ParsedJqlQueries](../schemas/Parsed/ParsedJqlQueries.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
