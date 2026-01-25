# Dashboards

This resource represents dashboards. Use it to obtain the details of dashboards as well as get, create, update, or remove item properties and gadgets from dashboards.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/dashboard` | Get all dashboards | [View](../operations/getAllDashboards.md) |
| POST | `/rest/api/3/dashboard` | Create dashboard | [View](../operations/createDashboard.md) |
| PUT | `/rest/api/3/dashboard/bulk/edit` | Bulk edit dashboards | [View](../operations/bulkEditDashboards.md) |
| GET | `/rest/api/3/dashboard/gadgets` | Get available gadgets | [View](../operations/getAllAvailableDashboardGadgets.md) |
| GET | `/rest/api/3/dashboard/search` | Search for dashboards | [View](../operations/getDashboardsPaginated.md) |
| GET | `/rest/api/3/dashboard/{dashboardId}/gadget` | Get gadgets | [View](../operations/getAllGadgets.md) |
| POST | `/rest/api/3/dashboard/{dashboardId}/gadget` | Add gadget to dashboard | [View](../operations/addGadget.md) |
| PUT | `/rest/api/3/dashboard/{dashboardId}/gadget/{gadgetId}` | Update gadget on dashboard | [View](../operations/updateGadget.md) |
| DELETE | `/rest/api/3/dashboard/{dashboardId}/gadget/{gadgetId}` | Remove gadget from dashboard | [View](../operations/removeGadget.md) |
| GET | `/rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties` | Get dashboard item property keys | [View](../operations/getDashboardItemPropertyKeys.md) |
| GET | `/rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}` | Get dashboard item property | [View](../operations/getDashboardItemProperty.md) |
| PUT | `/rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}` | Set dashboard item property | [View](../operations/setDashboardItemProperty.md) |
| DELETE | `/rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}` | Delete dashboard item property | [View](../operations/deleteDashboardItemProperty.md) |
| GET | `/rest/api/3/dashboard/{id}` | Get dashboard | [View](../operations/getDashboard.md) |
| PUT | `/rest/api/3/dashboard/{id}` | Update dashboard | [View](../operations/updateDashboard.md) |
| DELETE | `/rest/api/3/dashboard/{id}` | Delete dashboard | [View](../operations/deleteDashboard.md) |
| POST | `/rest/api/3/dashboard/{id}/copy` | Copy dashboard | [View](../operations/copyDashboard.md) |
