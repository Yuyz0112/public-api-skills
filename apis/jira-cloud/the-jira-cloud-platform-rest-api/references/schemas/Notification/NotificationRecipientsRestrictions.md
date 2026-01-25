# NotificationRecipientsRestrictions

Details of the group membership or permissions needed to receive the notification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `groupIds` | string[] | No | List of groupId memberships required to receive the notification. |
| `groups` | GroupName[] | No | List of group memberships required to receive the notification. |
| `permissions` | RestrictedPermission[] | No | List of permissions required to receive the notification. |

