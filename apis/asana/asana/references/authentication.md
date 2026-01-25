# Authentication

This document describes the authentication methods supported by this API.

## personalAccessToken

**Type:** http

A personal access token allows access to the api for the user who created it. This should be kept a secret and be treated like a password.

- **Scheme:** bearer

## oauth2

**Type:** oauth2

We require that applications designed to access the Asana API on behalf of multiple users implement OAuth 2.0.
Asana supports the Authorization Code Grant flow.

**authorizationCode flow:**
- Authorization URL: https://app.asana.com/-/oauth_authorize
- Token URL: https://app.asana.com/-/oauth_token
- Scopes:
  - `default`: Provides access to all endpoints documented in our API reference. If no scopes are requested, this scope is assumed by default.
  - `openid`: Provides access to OpenID Connect ID tokens and the OpenID Connect user info endpoint.
  - `email`: Provides access to the user’s email through the OpenID Connect user info endpoint.
  - `profile`: Provides access to the user’s name and profile photo through the OpenID Connect user info endpoint.
  - `attachments:read`: View access to attachments
  - `attachments:write`: Create and modify access to attachments
  - `attachments:delete`: Delete access to attachments
  - `custom_fields:read`: View access to custom fields
  - `custom_fields:write`: Create and modify access to custom fields
  - `goals:read`: View access to goals
  - `tasks:read`: View access to tasks
  - `tasks:write`: Create and modify access to tasks
  - `tasks:delete`: Delete access to tasks
  - `task_custom_types:read`: View access to task custom types
  - `task_templates:read`: View access to task templates
  - `team_memberships:read`: View access to team memberships
  - `portfolios:read`: View access to portfolios
  - `portfolios:write`: Create and modify access to portfolios
  - `project_templates:read`: View access to project templates
  - `projects:delete`: Delete access to projects
  - `projects:read`: View access to projects
  - `projects:write`: Create and modify access to projects
  - `users:read`: View access to users
  - `teams:read`: View access to teams
  - `time_tracking_entries:read`: View access to time tracking entries
  - `timesheet_approval_statuses:read`: View access to timesheet approval statuses
  - `timesheet_approval_statuses:write`: Create and modify access to timesheet approval statuses
  - `stories:read`: View access to stories
  - `stories:write`: Create and modify access to stories
  - `tags:read`: View access to tags
  - `tags:write`: Create and modify access to tags
  - `webhooks:read`: View access to webhooks
  - `webhooks:write`: Create and modify access to webhooks
  - `webhooks:delete`: Delete access to webhooks
  - `workspaces:read`: View access to workspaces

