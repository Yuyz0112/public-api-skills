# PUT /rest/api/3/uiModifications/{uiModificationId}

**Resource:** [UI modifications (apps)](../resources/UI-modifications-apps.md)
**Update UI modification**
**Operation ID:** `updateUiModification`

Updates a UI modification. UI modification can only be updated by Forge apps.

Each UI modification can define up to 1000 contexts. The same context can be assigned to maximum 100 UI modifications.

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

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uiModificationId` | path | string | Yes | The ID of the UI modification. |

## Request Body

Details of the UI modification.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateUiModificationDetails](../schemas/Update/UpdateUiModificationDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the UI modification is updated. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not from a Forge app. |
| 404 | Returned if the UI modification, a project, issue type, portal, or request type in the context are not found. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
