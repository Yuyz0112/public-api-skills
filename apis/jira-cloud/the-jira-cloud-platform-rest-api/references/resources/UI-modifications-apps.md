# UI modifications (apps)

UI modifications is a feature available for **Forge apps only**. It enables Forge apps to control how selected Jira and Jira Service Management fields behave on the following views:

 *  Jira global issue create
 *  Jira issue view
 *  Jira issue transition
 *  Jira Service Management request portal create.

For example: hide specific fields, set them as required, etc.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/uiModifications` | Get UI modifications | [View](../operations/getUiModifications.md) |
| POST | `/rest/api/3/uiModifications` | Create UI modification | [View](../operations/createUiModification.md) |
| PUT | `/rest/api/3/uiModifications/{uiModificationId}` | Update UI modification | [View](../operations/updateUiModification.md) |
| DELETE | `/rest/api/3/uiModifications/{uiModificationId}` | Delete UI modification | [View](../operations/deleteUiModification.md) |
