# PUT /rest/api/3/announcementBanner

**Resource:** [Announcement banner](../resources/Announcement-banner.md)
**Update announcement banner configuration**
**Operation ID:** `setBanner`

Updates the announcement banner configuration.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AnnouncementBannerConfigurationUpdate](../schemas/Announcement/AnnouncementBannerConfigurationUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if an invalid parameter is passed. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
