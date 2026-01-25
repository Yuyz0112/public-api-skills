# Filters

This resource represents [filters](https://confluence.atlassian.com/x/eQiiLQ). Use it to get, create, update, or delete filters. Also use it to configure the columns for a filter and set favorite filters.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/filter` | Create filter | [View](../operations/createFilter.md) |
| GET | `/rest/api/3/filter/favourite` | Get favorite filters | [View](../operations/getFavouriteFilters.md) |
| GET | `/rest/api/3/filter/my` | Get my filters | [View](../operations/getMyFilters.md) |
| GET | `/rest/api/3/filter/search` | Search for filters | [View](../operations/getFiltersPaginated.md) |
| GET | `/rest/api/3/filter/{id}` | Get filter | [View](../operations/getFilter.md) |
| PUT | `/rest/api/3/filter/{id}` | Update filter | [View](../operations/updateFilter.md) |
| DELETE | `/rest/api/3/filter/{id}` | Delete filter | [View](../operations/deleteFilter.md) |
| GET | `/rest/api/3/filter/{id}/columns` | Get columns | [View](../operations/getColumns.md) |
| PUT | `/rest/api/3/filter/{id}/columns` | Set columns | [View](../operations/setColumns.md) |
| DELETE | `/rest/api/3/filter/{id}/columns` | Reset columns | [View](../operations/resetColumns.md) |
| PUT | `/rest/api/3/filter/{id}/favourite` | Add filter as favorite | [View](../operations/setFavouriteForFilter.md) |
| DELETE | `/rest/api/3/filter/{id}/favourite` | Remove filter as favorite | [View](../operations/deleteFavouriteForFilter.md) |
| PUT | `/rest/api/3/filter/{id}/owner` | Change filter owner | [View](../operations/changeFilterOwner.md) |
