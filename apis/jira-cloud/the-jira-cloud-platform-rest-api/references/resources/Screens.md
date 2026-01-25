# Screens

This resource represents the screens used to record issue details. Use it to:

 *  get details of all screens.
 *  get details of all the fields available for use on screens.
 *  create screens.
 *  delete screens.
 *  update screens.
 *  add a field to the default screen.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/field/{fieldId}/screens` | Get screens for a field | [View](../operations/getScreensForField.md) |
| GET | `/rest/api/3/screens` | Get screens | [View](../operations/getScreens.md) |
| POST | `/rest/api/3/screens` | Create screen | [View](../operations/createScreen.md) |
| POST | `/rest/api/3/screens/addToDefault/{fieldId}` | Add field to default screen | [View](../operations/addFieldToDefaultScreen.md) |
| PUT | `/rest/api/3/screens/{screenId}` | Update screen | [View](../operations/updateScreen.md) |
| DELETE | `/rest/api/3/screens/{screenId}` | Delete screen | [View](../operations/deleteScreen.md) |
| GET | `/rest/api/3/screens/{screenId}/availableFields` | Get available screen fields | [View](../operations/getAvailableScreenFields.md) |
