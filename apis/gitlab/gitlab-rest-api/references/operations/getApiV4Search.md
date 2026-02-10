# GET /api/v4/search

**Resource:** [Search](../resources/Search.md)
**Search on GitLab**
**Operation ID:** `getApiV4Search`

This feature was introduced in GitLab 10.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | Yes | The expression it should be searched for |
| `scope` | query | enum: wiki_blobs, blobs, commits... | Yes | The scope of the search |
| `state` | query | enum: all, opened, closed... | No | Filter results by state |
| `confidential` | query | boolean | No | Filter results by confidentiality |
| `include_archived` | query | boolean | No | Includes archived projects in the search. Introduced in GitLab 18.9. |
| `fields` | query | any | No | Array of fields you wish to search. Available with advanced search. |
| `exclude_forks` | query | boolean | No | Excludes forked projects in the search. Available with exact code search. Introduced in GitLab 18.9. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

