# JQLQueryWithUnknownUsers

JQL queries that contained users that could not be found

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `convertedQuery` | string | No | The converted query, with accountIDs instead of user identifiers, or 'unknown' for users that could not be found |
| `originalQuery` | string | No | The original query, for reference |

