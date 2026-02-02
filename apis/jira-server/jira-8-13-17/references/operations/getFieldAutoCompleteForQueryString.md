# GET /jql/autocompletedata/suggestions

**Resource:** [jql](../resources/jql.md)
**Operation ID:** `getFieldAutoCompleteForQueryString`

Returns auto complete suggestions for JQL search.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldName` | query | string | No | the field name for which the suggestions are generated. |
| `fieldValue` | query | string | No | the portion of the field value that has already been provided by the user. |
| `predicateName` | query | string | No | the predicate for which the suggestions are generated. Suggestions are generated only for: "by", "from" and "to". |
| `predicateValue` | query | string | No | the portion of the predicate value that has already been provided by the user. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

