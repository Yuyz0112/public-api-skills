# GET /api/v4/projects/{id}/(-/)search

**Resource:** [Search](../resources/Search.md)
**Search on GitLab within a project**
**Operation ID:** `getApiV4ProjectsId()search`

This feature was introduced in GitLab 10.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `search` | query | string | Yes | The expression it should be searched for |
| `scope` | query | enum: issues, merge_requests, milestones... | Yes | The scope of the search |
| `ref` | query | string | No | The name of a repository branch or tag. If not given, the default branch is used |
| `state` | query | enum: all, opened, closed... | No | Filter results by state |
| `confidential` | query | boolean | No | Filter results by confidentiality |
| `fields` | query | any | No | Array of fields you wish to search. Available with advanced search. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

