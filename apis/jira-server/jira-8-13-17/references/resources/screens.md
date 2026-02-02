# screens

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/screens` |  | [View](../operations/getAllScreens.md) |
| POST | `/screens/addToDefault/{fieldId}` |  | [View](../operations/addFieldToDefaultScreen.md) |
| GET | `/screens/{screenId}/availableFields` |  | [View](../operations/getFieldsToAdd.md) |
| GET | `/screens/{screenId}/tabs` |  | [View](../operations/getAllTabs.md) |
| POST | `/screens/{screenId}/tabs` |  | [View](../operations/addTab.md) |
| PUT | `/screens/{screenId}/tabs/{tabId}` |  | [View](../operations/renameTab.md) |
| DELETE | `/screens/{screenId}/tabs/{tabId}` |  | [View](../operations/deleteTab.md) |
| GET | `/screens/{screenId}/tabs/{tabId}/fields` |  | [View](../operations/getAllFields.md) |
| POST | `/screens/{screenId}/tabs/{tabId}/fields` |  | [View](../operations/addField.md) |
| DELETE | `/screens/{screenId}/tabs/{tabId}/fields/{id}` |  | [View](../operations/removeField.md) |
| POST | `/screens/{screenId}/tabs/{tabId}/fields/{id}/move` |  | [View](../operations/moveField.md) |
| POST | `/screens/{screenId}/tabs/{tabId}/move/{pos}` |  | [View](../operations/moveTab.md) |
