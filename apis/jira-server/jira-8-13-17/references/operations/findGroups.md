# GET /groups/picker

**Resource:** [groups](../resources/groups.md)
**Operation ID:** `findGroups`

Returns groups with substrings matching a given query. This is mainly for use with
 the group picker, so the returned groups contain html to be used as picker suggestions.
 The groups are also wrapped in a single response object that also contains a header for
 use in the picker, specifically <i>Showing X of Y matching groups</i>.
 <p>
 The number of groups returned is limited by the system property "jira.ajax.autocomplete.limit"
 <p>
 The groups will be unique and sorted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | a String to match groups agains |
| `exclude` | query | string | No |  |
| `maxResults` | query | integer (int32) | No |  |
| `userName` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

