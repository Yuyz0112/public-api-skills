# AnnouncementBannerConfiguration

Announcement banner configuration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hashId` | string | No | Hash of the banner data. The client detects updates by comparing hash IDs. |
| `isDismissible` | boolean | No | Flag indicating if the announcement banner can be dismissed by the user. |
| `isEnabled` | boolean | No | Flag indicating if the announcement banner is enabled or not. |
| `message` | string | No | The text on the announcement banner. |
| `visibility` | enum: public, private | No | Visibility of the announcement banner. |

