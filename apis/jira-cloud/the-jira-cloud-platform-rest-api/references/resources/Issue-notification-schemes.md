# Issue notification schemes

This resource represents notification schemes, lists of events and the recipients who will receive notifications for those events. Use it to get details of a notification scheme and a list of notification schemes.

### About notification schemes ###

A notification scheme is a list of events and recipients who will receive notifications for those events. The list is contained within the `notificationSchemeEvents` object and contains pairs of `events` and `notifications`:

 *  `event` Identifies the type of event. The events can be [Jira system events](https://support.atlassian.com/jira-cloud-administration/docs/configure-notification-schemes/) (see the *Events* section) or [custom events](https://support.atlassian.com/jira-cloud-administration/docs/add-a-custom-event/).
 *  `notifications` Identifies the [recipients](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-recipientsRecipients) of notifications for each event. Recipients can be any of the following types:
    
     *  `CurrentAssignee`
     *  `Reporter`
     *  `CurrentUser`
     *  `ProjectLead`
     *  `ComponentLead`
     *  `User` (the `parameter` is the user key)
     *  `Group` (the `parameter` is the group name)
     *  `ProjectRole` (the `parameter` is the project role ID)
     *  `EmailAddress` *(deprecated)*
     *  `AllWatchers`
     *  `UserCustomField` (the `parameter` is the ID of the custom field)
     *  `GroupCustomField`(the `parameter` is the ID of the custom field)

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/notificationscheme` | Get notification schemes paginated | [View](../operations/getNotificationSchemes.md) |
| POST | `/rest/api/3/notificationscheme` | Create notification scheme | [View](../operations/createNotificationScheme.md) |
| GET | `/rest/api/3/notificationscheme/project` | Get projects using notification schemes paginated | [View](../operations/getNotificationSchemeToProjectMappings.md) |
| GET | `/rest/api/3/notificationscheme/{id}` | Get notification scheme | [View](../operations/getNotificationScheme.md) |
| PUT | `/rest/api/3/notificationscheme/{id}` | Update notification scheme | [View](../operations/updateNotificationScheme.md) |
| PUT | `/rest/api/3/notificationscheme/{id}/notification` | Add notifications to notification scheme | [View](../operations/addNotifications.md) |
| DELETE | `/rest/api/3/notificationscheme/{notificationSchemeId}` | Delete notification scheme | [View](../operations/deleteNotificationScheme.md) |
| DELETE | `/rest/api/3/notificationscheme/{notificationSchemeId}/notification/{notificationId}` | Remove notification from notification scheme | [View](../operations/removeNotificationFromNotificationScheme.md) |
