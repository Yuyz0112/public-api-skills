# GET /rest/api/3/jql/autocompletedata

**Resource:** [JQL](../resources/JQL.md)
**Get field reference data (GET)**
**Operation ID:** `getAutoComplete`

Returns reference data for JQL searches. This is a downloadable version of the documentation provided in [Advanced searching - fields reference](https://confluence.atlassian.com/x/gwORLQ) and [Advanced searching - functions reference](https://confluence.atlassian.com/x/hgORLQ), along with a list of JQL-reserved words. Use this information to assist with the programmatic creation of JQL queries or the validation of queries built in a custom query builder.

To filter visible field details by project or collapse non-unique fields by field type then [Get field reference data (POST)](#api-rest-api-3-jql-autocompletedata-post) can be used.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[JQLReferenceData](../schemas/JQLReferenceData/JQLReferenceData.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
