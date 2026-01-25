---
name: asana
description: This is the interface for interacting with the [Asana Platform](https://developers.asana.com). Our API reference is generated from our [OpenAPI spec] (https://raw.githubusercontent.com/Asana/openapi/m. Use when working with the Asana or when the user needs to interact with this API.
license: Apache 2.0 (https://www.apache.org/licenses/LICENSE-2.0)
metadata:
  api-version: "1.0"
  openapi-version: "3.0.0"
---

# Asana

This is the interface for interacting with the [Asana Platform](https://developers.asana.com). Our API reference is generated from our [OpenAPI spec] (https://raw.githubusercontent.com/Asana/openapi/m

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 42 resource index files
├── operations/     # 217 operation detail files
└── schemas/        # 47 schema groups, 244 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://app.asana.com/api/1.0` - Main endpoint.

## Authentication

Supported methods: **personalAccessToken**, **oauth2**. See `references/authentication.md` for details.

## Resources

- **Tasks** → `references/resources/Tasks.md` (27 ops) - The task is the basic object around which many ope
- **Projects** → `references/resources/Projects.md` (19 ops) - A project represents a prioritized list of tasks i
- **Goals** → `references/resources/Goals.md` (12 ops) - A goal is an object in the goal-tracking system th
- **Portfolios** → `references/resources/Portfolios.md` (12 ops) - A portfolio gives a high-level overview of the sta
- **Custom fields** → `references/resources/Custom-fields.md` (8 ops) - _Note: Custom fields are a premium feature. Integr
- **Tags** → `references/resources/Tags.md` (8 ops) - A tag is a label that can be attached to any task 
- **Users** → `references/resources/Users.md` (8 ops) - A user object represents an account in Asana that 
- **Sections** → `references/resources/Sections.md` (7 ops) - A section is a subdivision of a project that group
- **Teams** → `references/resources/Teams.md` (7 ops) - A team is used to group related projects and peopl
- **Time tracking entries** → `references/resources/Time-tracking-entries.md` (6 ops) - Asana's native time tracking feature allows you to
- **Workspaces** → `references/resources/Workspaces.md` (6 ops) - A *workspace* is the highest-level organizational 
- **Allocations** → `references/resources/Allocations.md` (5 ops) - An allocation object represents how much of a reso
- **Budgets** → `references/resources/Budgets.md` (5 ops) - A *budget* object represents a budget for a specif
- **Goal relationships** → `references/resources/Goal-relationships.md` (5 ops) - A goal relationship is an object representing the 
- **Memberships** → `references/resources/Memberships.md` (5 ops) - A membership object represents the relationship be
- **Project templates** → `references/resources/Project-templates.md` (5 ops) - A project template is an object that allows new pr
- **Rates** → `references/resources/Rates.md` (5 ops) - A rate object represents the rate of a resource fo
- **Stories** → `references/resources/Stories.md` (5 ops) - *See [our forum post](https://forum.asana.com/t/no
- **Webhooks** → `references/resources/Webhooks.md` (5 ops) - Webhooks allow you to subscribe to notifications a
- **Access requests** → `references/resources/Access-requests.md` (4 ops) - An access request object represents a user's reque
- **Attachments** → `references/resources/Attachments.md` (4 ops) - An *attachment* object represents any file attache
- **Custom field settings** → `references/resources/Custom-field-settings.md` (4 ops) - Custom fields are attached to a particular project
- **Project briefs** → `references/resources/Project-briefs.md` (4 ops) - A project brief object represents a rich text docu
- **Project statuses** → `references/resources/Project-statuses.md` (4 ops) - *Deprecated: new integrations should prefer using 
- **Status updates** → `references/resources/Status-updates.md` (4 ops) - A status update is an update on the progress of a 
- **Task templates** → `references/resources/Task-templates.md` (4 ops) - A task template is an object that allows new tasks
- **Team memberships** → `references/resources/Team-memberships.md` (4 ops) - This object determines if a user is a member of a 
- **Portfolio memberships** → `references/resources/Portfolio-memberships.md` (3 ops) - This object determines if a user is a member of a 
- **Workspace memberships** → `references/resources/Workspace-memberships.md` (3 ops) - This object determines if a user is a member of a 
- **Custom types** → `references/resources/Custom-types.md` (2 ops) - A custom type allows distinct categorizations of o
- **Exports** → `references/resources/Exports.md` (2 ops) - Exports are a way to download data from Asana. The
- **Organization exports** → `references/resources/Organization-exports.md` (2 ops) - An `organization_export` object represents a reque
- **Project memberships** → `references/resources/Project-memberships.md` (2 ops) - With the introduction of “comment-only” projects i
- **Time periods** → `references/resources/Time-periods.md` (2 ops) - A time period is an object that represents a domai
- **User task lists** → `references/resources/User-task-lists.md` (2 ops) - A user task list represents the tasks assigned to 
- **Audit log API** → `references/resources/Audit-log-API.md` (1 ops) - Asana's audit log is an immutable log of [importan
- **Batch API** → `references/resources/Batch-API.md` (1 ops) - There are many cases where you want to accomplish 
- **Events** → `references/resources/Events.md` (1 ops) - An event is an object representing a change to a r
- **Jobs** → `references/resources/Jobs.md` (1 ops) - Jobs represent processes that handle asynchronous 
- **Reactions** → `references/resources/Reactions.md` (1 ops) - A reaction is an object that represents a user's e
- **Rules** → `references/resources/Rules.md` (1 ops) - [Asana rules](https://help.asana.com/s/article/rul
- **Typeahead** → `references/resources/Typeahead.md` (1 ops) - The typeahead search API provides search for objec
