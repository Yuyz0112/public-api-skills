# POST /rest/api/3/jql/autocompletedata

**Resource:** [JQL](../resources/JQL.md)
**Get field reference data (POST)**
**Operation ID:** `getAutoCompletePost`

Returns reference data for JQL searches. This is a downloadable version of the documentation provided in [Advanced searching - fields reference](https://confluence.atlassian.com/x/gwORLQ) and [Advanced searching - functions reference](https://confluence.atlassian.com/x/hgORLQ), along with a list of JQL-reserved words. Use this information to assist with the programmatic creation of JQL queries or the validation of queries built in a custom query builder.

This operation can filter the custom fields returned by project. Invalid project IDs in `projectIds` are ignored. System fields are always returned.

It can also return the collapsed field for custom fields. Collapsed fields enable searches to be performed across all fields with the same name and of the same field type. For example, the collapsed field `Component - Component[Dropdown]` enables dropdown fields `Component - cf[10061]` and `Component - cf[10062]` to be searched simultaneously.

**[Permissions](#permissions) required:** None.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SearchAutoCompleteFilter](../schemas/Search/SearchAutoCompleteFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[JQLReferenceData](../schemas/JQLReferenceData/JQLReferenceData.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
