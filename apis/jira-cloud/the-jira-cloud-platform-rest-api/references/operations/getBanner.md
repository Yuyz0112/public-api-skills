# GET /rest/api/3/announcementBanner

**Resource:** [Announcement banner](../resources/Announcement-banner.md)
**Get announcement banner configuration**
**Operation ID:** `getBanner`

Returns the current announcement banner configuration.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[AnnouncementBannerConfiguration](../schemas/Announcement/AnnouncementBannerConfiguration.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
