# GET /rest/api/3/jql/autocompletedata/suggestions

**Resource:** [JQL](../resources/JQL.md)
**Get field auto complete suggestions**
**Operation ID:** `getFieldAutoCompleteForQueryString`

Returns the JQL search auto complete suggestions for a field.

Suggestions can be obtained by providing:

 *  `fieldName` to get a list of all values for the field.
 *  `fieldName` and `fieldValue` to get a list of values containing the text in `fieldValue`.
 *  `fieldName` and `predicateName` to get a list of all predicate values for the field.
 *  `fieldName`, `predicateName`, and `predicateValue` to get a list of predicate values containing the text in `predicateValue`.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldName` | query | string | No | The name of the field. |
| `fieldValue` | query | string | No | The partial field item name entered by the user. |
| `predicateName` | query | string | No | The name of the [ CHANGED operator predicate](https://confluence.atlassian.com/x/hQORLQ#Advancedsearching-operatorsreference-CHANGEDCHANGED) for which the suggestions are generated. The valid predicate operators are *by*, *from*, and *to*. |
| `predicateValue` | query | string | No | The partial predicate item name entered by the user. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if an invalid combination of parameters is passed. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[AutoCompleteSuggestions](../schemas/Auto/AutoCompleteSuggestions.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
