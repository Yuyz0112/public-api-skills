# JQL

This resource represents JQL search auto-complete details. Use it to obtain JQL search auto-complete data and suggestions for use in programmatic construction of queries or custom query builders. It also provides operations to:

 *  convert one or more JQL queries with user identifiers (username or user key) to equivalent JQL queries with account IDs.
 *  convert readable details in one or more JQL queries to IDs where a user doesn't have permission to view the entity whose details are readable.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/jql/autocompletedata` | Get field reference data (GET) | [View](../operations/getAutoComplete.md) |
| POST | `/rest/api/3/jql/autocompletedata` | Get field reference data (POST) | [View](../operations/getAutoCompletePost.md) |
| GET | `/rest/api/3/jql/autocompletedata/suggestions` | Get field auto complete suggestions | [View](../operations/getFieldAutoCompleteForQueryString.md) |
| POST | `/rest/api/3/jql/parse` | Parse JQL query | [View](../operations/parseJqlQueries.md) |
| POST | `/rest/api/3/jql/pdcleaner` | Convert user identifiers to account IDs in JQL queries | [View](../operations/migrateQueries.md) |
| POST | `/rest/api/3/jql/sanitize` | Sanitize JQL queries | [View](../operations/sanitiseJqlQueries.md) |
