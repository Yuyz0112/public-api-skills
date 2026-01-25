---
name: the-jira-cloud-platform-rest-api
description: Jira Cloud platform REST API documentation. Use when working with the The Jira Cloud platform REST API or when the user needs to interact with this API.
license: Apache 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html)
metadata:
  api-version: "1001.0.0-SNAPSHOT-3a3f5db9e8b3df6387b44b4333e4ed0a2c13a528"
  openapi-version: "3.0.1"
  contact: "ecosystem@atlassian.com"
---

# The Jira Cloud platform REST API

Jira Cloud platform REST API documentation

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 99 resource index files
├── operations/     # 616 operation detail files
└── schemas/        # 197 schema groups, 967 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://your-domain.atlassian.net`

## Authentication

Supported methods: **OAuth2**, **basicAuth**. See `references/authentication.md` for details.

## Resources

- **Issues** → `references/resources/Issues.md` (23 ops) - This resource represents Jira issues. Use it to:


- **Workflow schemes** → `references/resources/Workflow-schemes.md` (19 ops) - This resource represents workflow schemes. Use it 
- **Workflows** → `references/resources/Workflows.md` (18 ops) - This resource represents workflows. Use it to:

 *
- **Dashboards** → `references/resources/Dashboards.md` (17 ops) - This resource represents dashboards. Use it to obt
- **Issue security schemes** → `references/resources/Issue-security-schemes.md` (16 ops) - This resource represents issue security schemes. U
- **Issue field configurations** → `references/resources/Issue-field-configurations.md` (15 ops) - This resource represents issue field configuration
- **Project versions** → `references/resources/Project-versions.md` (15 ops) - This resource represents project versions. Use it 
- **Field schemes** → `references/resources/Field-schemes.md` (14 ops) - This resource represents field schemes which are r
- **Workflow scheme drafts** → `references/resources/Workflow-scheme-drafts.md` (14 ops) - This resource represents draft workflow schemes. U
- **Issue custom field contexts** → `references/resources/Issue-custom-field-contexts.md` (13 ops) - This resource represents issue custom field contex
- **Filters** → `references/resources/Filters.md` (13 ops) - This resource represents [filters](https://conflue
- **Projects** → `references/resources/Projects.md` (13 ops) - This resource represents projects. Use it to get, 
- **Users** → `references/resources/Users.md` (13 ops) - This resource represent users. Use it to:

 *  get
- **Issue type screen schemes** → `references/resources/Issue-type-screen-schemes.md` (11 ops) - This resource represents issue type screen schemes
- **Issue fields** → `references/resources/Issue-fields.md` (10 ops) - This resource represents issue fields, both system
- **Issue worklogs** → `references/resources/Issue-worklogs.md` (10 ops) - This resource represents issue worklogs. Use it to
- **Issue type schemes** → `references/resources/Issue-type-schemes.md` (10 ops) - This resource represents issue type schemes in cla
- **Issue bulk operations** → `references/resources/Issue-bulk-operations.md` (9 ops) - This resource represents the issue bulk operations
- **Permission schemes** → `references/resources/Permission-schemes.md` (9 ops) - This resource represents permission schemes. Use i
- **Teams in plan** → `references/resources/Teams-in-plan.md` (9 ops) - This resource represents planning settings for pla
- **Project roles** → `references/resources/Project-roles.md` (9 ops) - This resource represents the roles that users can 
- **Status** → `references/resources/Status.md` (9 ops) - This resource represents statuses. Use it to searc
- **Issue attachments** → `references/resources/Issue-attachments.md` (8 ops) - This resource represents issue attachments and the
- **Project components** → `references/resources/Project-components.md` (8 ops) - This resource represents project components. Use i
- **Issue custom field options (apps)** → `references/resources/Issue-custom-field-options-apps.md` (8 ops) - This resource represents custom issue field select
- **Groups** → `references/resources/Groups.md` (8 ops) - This resource represents groups of users. Use it t
- **Issue properties** → `references/resources/Issue-properties.md` (8 ops) - This resource represents [issue](#api-group-Issues
- **Issue types** → `references/resources/Issue-types.md` (8 ops) - This resource represents issues types. Use it to:

- **Issue notification schemes** → `references/resources/Issue-notification-schemes.md` (8 ops) - This resource represents notification schemes, lis
- **Issue priorities** → `references/resources/Issue-priorities.md` (8 ops) - This resource represents issue priorities. Use it 
- **Priority schemes** → `references/resources/Priority-schemes.md` (8 ops) - This resource represents issue priority schemes. U
- **Issue resolutions** → `references/resources/Issue-resolutions.md` (8 ops) - This resource represents issue resolution values. 
- **User search** → `references/resources/User-search.md` (8 ops) - This resource represents various ways to search fo
- **App properties** → `references/resources/App-properties.md` (8 ops) - This resource represents app properties. Use it to
- **Avatars** → `references/resources/Avatars.md` (7 ops) - This resource represents system and custom avatars
- **Issue custom field options** → `references/resources/Issue-custom-field-options.md` (7 ops) - This resource represents custom issue field select
- **Screens** → `references/resources/Screens.md` (7 ops) - This resource represents the screens used to recor
- **Issue search** → `references/resources/Issue-search.md` (7 ops) - This resource represents various ways to search fo
- **Plans** → `references/resources/Plans.md` (7 ops) - This resource represents plans. Use it to get, cre
- **Issue comments** → `references/resources/Issue-comments.md` (6 ops) - This resource represents issue comments. Use it to
- **Filter sharing** → `references/resources/Filter-sharing.md` (6 ops) - This resource represents options for sharing [filt
- **Issue remote links** → `references/resources/Issue-remote-links.md` (6 ops) - This resource represents remote issue links, a way
- **JQL** → `references/resources/JQL.md` (6 ops) - This resource represents JQL search auto-complete 
- **Myself** → `references/resources/Myself.md` (6 ops) - This resource represents information about the cur
- **Project role actors** → `references/resources/Project-role-actors.md` (6 ops) - This resource represents the users assigned to [pr
- **Screen tabs** → `references/resources/Screen-tabs.md` (6 ops) - This resource represents the screen tabs used to r
- **Time tracking** → `references/resources/Time-tracking.md` (5 ops) - This resource represents time tracking and time tr
- **Issue link types** → `references/resources/Issue-link-types.md` (5 ops) - This resource represents [issue link](#api-group-I
- **Project templates** → `references/resources/Project-templates.md` (5 ops) - This resource represents project templates. Use it
- **Project categories** → `references/resources/Project-categories.md` (5 ops) - This resource represents project categories. Use i
- **Webhooks** → `references/resources/Webhooks.md` (5 ops) - This resource represents webhooks. Webhooks are ca
- **Jira settings** → `references/resources/Jira-settings.md` (4 ops) - This resource represents various settings in Jira.
- **Issue comment properties** → `references/resources/Issue-comment-properties.md` (4 ops) - This resource represents [issue comment](#api-grou
- **Issue watchers** → `references/resources/Issue-watchers.md` (4 ops) - This resource represents users watching an issue. 
- **Issue worklog properties** → `references/resources/Issue-worklog-properties.md` (4 ops) - This resource represents [issue worklog](#api-grou
- **Issue type properties** → `references/resources/Issue-type-properties.md` (4 ops) - This resource represents [issue type](#api-group-I
- **Permissions** → `references/resources/Permissions.md` (4 ops) - This resource represents permissions. Use it to ob
- **Project types** → `references/resources/Project-types.md` (4 ops) - This resource represents project types. Use it to 
- **Project avatars** → `references/resources/Project-avatars.md` (4 ops) - This resource represents avatars associated with a
- **Project properties** → `references/resources/Project-properties.md` (4 ops) - This resource represents [project](#api-group-Proj
- **Project permission schemes** → `references/resources/Project-permission-schemes.md` (4 ops) - This resource represents permission schemes for a 
- **Screen tab fields** → `references/resources/Screen-tab-fields.md` (4 ops) - This resource represents the screen tab fields use
- **Screen schemes** → `references/resources/Screen-schemes.md` (4 ops) - This resource represents screen schemes in classic
- **UI modifications (apps)** → `references/resources/UI-modifications-apps.md` (4 ops) - UI modifications is a feature available for **Forg
- **User properties** → `references/resources/User-properties.md` (4 ops) - This resource represents [user](#api-group-Users) 
- **Workflow transition properties** → `references/resources/Workflow-transition-properties.md` (4 ops) - This resource represents workflow transition prope
- **Issue custom field configuration (apps)** → `references/resources/Issue-custom-field-configuration-apps.md` (3 ops) - This resource represents configurations stored aga
- **Jira expressions** → `references/resources/Jira-expressions.md` (3 ops) - This resource is a collection of operations for [J
- **License metrics** → `references/resources/License-metrics.md` (3 ops) - This resource represents license metrics. Use it t
- **Issue votes** → `references/resources/Issue-votes.md` (3 ops) - This resource represents votes cast by users on an
- **Issue links** → `references/resources/Issue-links.md` (3 ops) - This resource represents links between issues. Use
- **JQL functions (apps)** → `references/resources/JQL-functions-apps.md` (3 ops) - This resource represents JQL function's precomputa
- **Project classification levels** → `references/resources/Project-classification-levels.md` (3 ops) - This resource represents classification levels use
- **Project key and name validation** → `references/resources/Project-key-and-name-validation.md` (3 ops) - This resource provides validation for project keys
- **Workflow transition rules** → `references/resources/Workflow-transition-rules.md` (3 ops) - This resource represents workflow transition rules
- **Dynamic modules** → `references/resources/Dynamic-modules.md` (3 ops) - This resource represents [modules registered dynam
- **App migration** → `references/resources/App-migration.md` (3 ops) - This resource supports [app migrations](https://de
- **Announcement banner** → `references/resources/Announcement-banner.md` (2 ops) - This resource represents an announcement banner. U
- **Issue custom field values (apps)** → `references/resources/Issue-custom-field-values-apps.md` (2 ops) - This resource represents the values of custom fiel
- **Application roles** → `references/resources/Application-roles.md` (2 ops) - This resource represents application roles. Use it
- **App data policies** → `references/resources/App-data-policies.md` (2 ops) - This resource represents app access rule data poli
- **Issue custom field associations** → `references/resources/Issue-custom-field-associations.md` (2 ops) - This resource represents the fields associated to 
- **Issue security level** → `references/resources/Issue-security-level.md` (2 ops) - This resource represents issue security levels. Us
- **Project features** → `references/resources/Project-features.md` (2 ops) - This resource represents project features. Use it 
- **Project email** → `references/resources/Project-email.md` (2 ops) - This resource represents the email address used to
- **Issue redaction** → `references/resources/Issue-redaction.md` (2 ops) - This resource represents Issue Redaction. Provides
- **Issue navigator settings** → `references/resources/Issue-navigator-settings.md` (2 ops) - This resource represents issue navigator settings.
- **Workflow statuses** → `references/resources/Workflow-statuses.md` (2 ops) - This resource represents issue workflow statuses. 
- **Workflow status categories** → `references/resources/Workflow-status-categories.md` (2 ops) - This resource represents status categories. Use it
- **Tasks** → `references/resources/Tasks.md` (2 ops) - This resource represents a [long-running asynchron
- **Workflow scheme project associations** → `references/resources/Workflow-scheme-project-associations.md` (2 ops) - This resource represents the associations between 
- **Audit records** → `references/resources/Audit-records.md` (1 ops) - This resource represents audits that record activi
- **Classification levels** → `references/resources/Classification-levels.md` (1 ops) - This resource represents classification levels.
- **Group and user picker** → `references/resources/Group-and-user-picker.md` (1 ops) - This resource represents a list of users and a lis
- **Labels** → `references/resources/Labels.md` (1 ops) - This resource represents available labels. Use it 
- **Server info** → `references/resources/Server-info.md` (1 ops) - This resource provides information about the Jira 
- **Migration of Connect modules to Forge** → `references/resources/Migration-of-Connect-modules-to-Forge.md` (1 ops) - This resource supports the migration of some Conne
- **Service Registry** → `references/resources/Service-Registry.md` (1 ops) - This resource represents a service registry. Use i
- **rest** → `references/resources/rest.md` (1 ops)
