# Authentication

This document describes the authentication methods supported by this API.

## PersonalAccessToken

**Type:** apiKey

- **In:** header

## OAuth2

**Type:** oauth2

**authorizationCode flow:**
- Authorization URL: https://www.figma.com/oauth
- Token URL: https://api.figma.com/v1/oauth/token
- Scopes:
  - `current_user:read`: Read your name, email, and profile image.
  - `file_comments:read`: Read the comments for files.
  - `file_comments:write`: Post and delete comments and comment reactions in files.
  - `file_content:read`: Read the contents of files, such as nodes and the editor type.
  - `file_dev_resources:read`: Read dev resources in files.
  - `file_dev_resources:write`: Write to dev resources in files.
  - `file_metadata:read`: Read metadata of files.
  - `file_variables:read`: Read variables in Figma file. Note: this is only available to members in Enterprise organizations.
  - `file_variables:write`: Write to variables in Figma file. Note: this is only available to members in Enterprise organizations.
  - `file_versions:read`: Read the version history for files you can access.
  - `files:read`: Deprecated. Read files, projects, users, versions, comments, components & styles, and webhooks.
  - `library_analytics:read`: Read library analytics data.
  - `library_assets:read`: Read data of individual published components and styles.
  - `library_content:read`: Read published components and styles of files.
  - `projects:read`: List projects and files in projects.
  - `team_library_content:read`: Read published components and styles of teams.
  - `webhooks:read`: Read metadata of webhooks.
  - `webhooks:write`: Create and manage webhooks.

## OrgOAuth2

**Type:** oauth2

**authorizationCode flow:**
- Authorization URL: https://www.figma.com/oauth
- Token URL: https://api.figma.com/v1/oauth/token
- Scopes:
  - `org:activity_log_read`: Read activity logs in the organization.

