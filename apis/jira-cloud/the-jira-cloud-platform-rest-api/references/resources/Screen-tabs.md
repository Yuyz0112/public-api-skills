# Screen tabs

This resource represents the screen tabs used to record issue details. Use it to get, create, update, move, and delete screen tabs.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/screens/tabs` | Get bulk screen tabs | [View](../operations/getBulkScreenTabs.md) |
| GET | `/rest/api/3/screens/{screenId}/tabs` | Get all screen tabs | [View](../operations/getAllScreenTabs.md) |
| POST | `/rest/api/3/screens/{screenId}/tabs` | Create screen tab | [View](../operations/addScreenTab.md) |
| PUT | `/rest/api/3/screens/{screenId}/tabs/{tabId}` | Update screen tab | [View](../operations/renameScreenTab.md) |
| DELETE | `/rest/api/3/screens/{screenId}/tabs/{tabId}` | Delete screen tab | [View](../operations/deleteScreenTab.md) |
| POST | `/rest/api/3/screens/{screenId}/tabs/{tabId}/move/{pos}` | Move screen tab | [View](../operations/moveScreenTab.md) |
