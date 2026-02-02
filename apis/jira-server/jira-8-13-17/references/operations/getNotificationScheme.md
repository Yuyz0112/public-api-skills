# GET /notificationscheme/{id}

**Resource:** [notificationscheme](../resources/notificationscheme.md)
**Operation ID:** `getNotificationScheme`

Returns a full representation of the notification scheme for the given id. This resource will return a
 notification scheme containing a list of events and recipient configured to receive notifications for these events. Consumer
 should allow events without recipients to appear in response. User accessing
 the data is required to have permissions to administer at least one project associated with the requested notification scheme.
 <p>
 Notification recipients can be:
 <ul>
 <li>current assignee - the value of the notificationType is CurrentAssignee</li>
 <li>issue reporter - the value of the notificationType is Reporter</li>
 <li>current user - the value of the notificationType is CurrentUser</li>
 <li>project lead - the value of the notificationType is ProjectLead</li>
 <li>component lead - the value of the notificationType is ComponentLead</li>
 <li>all watchers - the value of the notification type is AllWatchers</li>
 <li>configured user - the value of the notification type is User. Parameter will contain key of the user. Information about the user will be provided
 if <b>user</b> expand parameter is used. </li>
 <li>configured group - the value of the notification type is Group. Parameter will contain name of the group. Information about the group will be provided
 if <b>group</b> expand parameter is used. </li>
 <li>configured email address - the value of the notification type is EmailAddress, additionally information about the email will be provided.</li>
 <li>users or users in groups in the configured custom fields - the value of the notification type is UserCustomField or GroupCustomField. Parameter
 will contain id of the custom field. Information about the field will be provided if <b>field</b> expand parameter is used. </li>
 <li>configured project role - the value of the notification type is ProjectRole. Parameter will contain project role id. Information about the project role
 will be provided if <b>projectRole</b> expand parameter is used. </li>
 </ul>
 Please see the example for reference.
 </p>
 The events can be Jira system events or events configured by administrator. In case of the system events, data about theirs
 ids, names and descriptions is provided. In case of custom events, the template event is included as well.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

