---
name: slack-web-api
description: One way to interact with the Slack platform is its HTTP RPC-based Web API, a collection of methods requiring OAuth 2.0-based user, bot, or workspace tokens blessed with related OAuth scopes.. Use when working with the Slack Web API or when the user needs to interact with this API.
metadata:
  api-version: "1.7.0"
  openapi-version: "3.0.0"
---

# Slack Web API

One way to interact with the Slack platform is its HTTP RPC-based Web API, a collection of methods requiring OAuth 2.0-based user, bot, or workspace tokens blessed with related OAuth scopes.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 56 resource index files
├── operations/     # 253 operation detail files
└── schemas/        # 3 schema groups, 48 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://slack.com/api`

## Authentication

Supported methods: **slackAuth**. See `references/authentication.md` for details.

## Resources

- **admin** → `references/resources/admin.md` (56 ops)
- **conversations** → `references/resources/conversations.md` (18 ops)
- **admin.conversations** → `references/resources/admin-conversations.md` (13 ops)
- **files** → `references/resources/files.md` (13 ops)
- **users** → `references/resources/users.md` (12 ops)
- **chat** → `references/resources/chat.md` (10 ops)
- **admin.users** → `references/resources/admin-users.md` (8 ops)
- **apps** → `references/resources/apps.md` (8 ops)
- **usergroups** → `references/resources/usergroups.md` (7 ops)
- **admin.teams.settings** → `references/resources/admin-teams-settings.md` (6 ops)
- **calls** → `references/resources/calls.md` (6 ops)
- **files.remote** → `references/resources/files-remote.md` (6 ops)
- **admin.emoji** → `references/resources/admin-emoji.md` (5 ops)
- **dnd** → `references/resources/dnd.md` (5 ops)
- **reminders** → `references/resources/reminders.md` (5 ops)
- **team** → `references/resources/team.md` (5 ops)
- **admin.usergroups** → `references/resources/admin-usergroups.md` (4 ops)
- **reactions** → `references/resources/reactions.md` (4 ops)
- **views** → `references/resources/views.md` (4 ops)
- **admin.conversations.restrictAccess** → `references/resources/admin-conversations-restrictAccess.md` (3 ops)
- **admin.inviteRequests** → `references/resources/admin-inviteRequests.md` (3 ops)
- **oauth** → `references/resources/oauth.md` (3 ops)
- **pins** → `references/resources/pins.md` (3 ops)
- **stars** → `references/resources/stars.md` (3 ops)
- **workflows** → `references/resources/workflows.md` (3 ops)
- **admin.apps** → `references/resources/admin-apps.md` (2 ops)
- **admin.teams** → `references/resources/admin-teams.md` (2 ops)
- **admin.users.session** → `references/resources/admin-users-session.md` (2 ops)
- **apps.permissions** → `references/resources/apps-permissions.md` (2 ops)
- **apps.permissions.users** → `references/resources/apps-permissions-users.md` (2 ops)
- **auth** → `references/resources/auth.md` (2 ops)
- **calls.participants** → `references/resources/calls-participants.md` (2 ops)
- **usergroups.users** → `references/resources/usergroups-users.md` (2 ops)
- **users.profile** → `references/resources/users-profile.md` (2 ops)
- **admin.apps.approved** → `references/resources/admin-apps-approved.md` (1 ops)
- **admin.apps.requests** → `references/resources/admin-apps-requests.md` (1 ops)
- **admin.apps.restricted** → `references/resources/admin-apps-restricted.md` (1 ops)
- **admin.conversations.ekm** → `references/resources/admin-conversations-ekm.md` (1 ops)
- **admin.inviteRequests.approved** → `references/resources/admin-inviteRequests-approved.md` (1 ops)
- **admin.inviteRequests.denied** → `references/resources/admin-inviteRequests-denied.md` (1 ops)
- **admin.teams.admins** → `references/resources/admin-teams-admins.md` (1 ops)
- **admin.teams.owners** → `references/resources/admin-teams-owners.md` (1 ops)
- **api** → `references/resources/api.md` (1 ops)
- **apps.event.authorizations** → `references/resources/apps-event-authorizations.md` (1 ops)
- **apps.permissions.resources** → `references/resources/apps-permissions-resources.md` (1 ops)
- **apps.permissions.scopes** → `references/resources/apps-permissions-scopes.md` (1 ops)
- **bots** → `references/resources/bots.md` (1 ops)
- **chat.scheduledMessages** → `references/resources/chat-scheduledMessages.md` (1 ops)
- **dialog** → `references/resources/dialog.md` (1 ops)
- **emoji** → `references/resources/emoji.md` (1 ops)
- **files.comments** → `references/resources/files-comments.md` (1 ops)
- **migration** → `references/resources/migration.md` (1 ops)
- **oauth.v2** → `references/resources/oauth-v2.md` (1 ops)
- **rtm** → `references/resources/rtm.md` (1 ops)
- **search** → `references/resources/search.md` (1 ops)
- **team.profile** → `references/resources/team-profile.md` (1 ops)
