# Issue search

This resource represents various ways to search for issues. Use it to search for issues with a JQL query and find issues to populate an issue picker.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issue/picker` | Get issue picker suggestions | [View](../operations/getIssuePickerResource.md) |
| POST | `/rest/api/3/jql/match` | Check issues against JQL | [View](../operations/matchIssues.md) |
| GET | `/rest/api/3/search` | Currently being removed. Search for issues using JQL (GET) | [View](../operations/searchForIssuesUsingJql.md) |
| POST | `/rest/api/3/search` | Currently being removed. Search for issues using JQL (POST) | [View](../operations/searchForIssuesUsingJqlPost.md) |
| POST | `/rest/api/3/search/approximate-count` | Count issues using JQL | [View](../operations/countIssues.md) |
| GET | `/rest/api/3/search/jql` | Search for issues using JQL enhanced search (GET) | [View](../operations/searchAndReconsileIssuesUsingJql.md) |
| POST | `/rest/api/3/search/jql` | Search for issues using JQL enhanced search (POST) | [View](../operations/searchAndReconsileIssuesUsingJqlPost.md) |
