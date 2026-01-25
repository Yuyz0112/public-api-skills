# POST /rest/api/3/uiModifications

**Resource:** [UI modifications (apps)](../resources/UI-modifications-apps.md)
**Create UI modification**
**Operation ID:** `createUiModification`

Creates a UI modification. UI modification can only be created by Forge apps.

Each app can define up to 3000 UI modifications. Each UI modification can define up to 1000 contexts. The same context can be assigned to maximum 100 UI modifications.

**Context types:**

 *  **Jira contexts:** For Jira view types, use `projectId` and `issueTypeId`. One field can act as a wildcard. Supported Jira views:
    
     *  `GIC` \- Jira global issue create
     *  `IssueView` \- Jira issue view
     *  `IssueTransition` \- Jira issue transition
 *  **Jira Service Management contexts:** For Jira Service Management view types, use `portalId` and `requestTypeId`. Wildcards are not supported. Supported JSM views:
    
     *  `JSMRequestCreate` \- Jira Service Management request create portal view

**[Permissions](#permissions) required:**

 *  *None* if the UI modification is created without contexts.
 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for one or more projects, if the UI modification is created with contexts.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Request Body

Details of the UI modification.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateUiModificationDetails](../schemas/Create/CreateUiModificationDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the UI modification is created. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not from a Forge app. |
| 404 | Returned if a project, issue type, portal, or request type in the context are not found. |

**Success Response Schema:**

[UiModificationIdentifiers](../schemas/Ui/UiModificationIdentifiers.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
