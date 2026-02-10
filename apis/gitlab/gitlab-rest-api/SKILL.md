---
name: gitlab-rest-api
description: GitLab REST API used to interact with a GitLab installation.. Use when working with the GitLab REST API or when the user needs to interact with this API.
metadata:
  api-version: "v4"
  openapi-version: "3.0.0"
---

# GitLab REST API

GitLab REST API used to interact with a GitLab installation.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 176 resource index files
├── operations/     # 1837 operation detail files
└── schemas/        # 428 schema groups, 454 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://gitlab.com/api` - GitLab REST API

## Authentication

Supported methods: **http**, **oauth2**. See `references/authentication.md` for details.

## Resources

- **Packages** → `references/resources/Packages.md` (189 ops) - Operations related to packages.
- **Integrations** → `references/resources/Integrations.md` (171 ops) - Operations related to integrations.
- **Projects** → `references/resources/Projects.md` (73 ops) - Operations related to projects.
- **Virtual registries** → `references/resources/Virtual-registries.md` (47 ops) - Operations related to virtual registries.
- **Discussions** → `references/resources/Discussions.md` (43 ops) - Operations related to discussions.
- **Users** → `references/resources/Users.md` (35 ops) - Operations related to users.
- **Notes** → `references/resources/Notes.md` (35 ops) - Operations related to notes.
- **Groups** → `references/resources/Groups.md` (34 ops) - Operations related to groups.
- **Merge requests** → `references/resources/Merge-requests.md` (33 ops) - Operations related to merge requests.
- **Award emoji** → `references/resources/Award-emoji.md` (32 ops) - Operations related to award emoji.
- **Mlops** → `references/resources/Mlops.md` (28 ops) - Operations related to mlops.
- **Epics** → `references/resources/Epics.md` (26 ops) - Operations related to epics.
- **Geo** → `references/resources/Geo.md` (25 ops) - Operations related to geo.
- **Deploy resources** → `references/resources/Deploy-resources.md` (25 ops) - Operations related to deploy resources.
- **Keys** → `references/resources/Keys.md` (23 ops) - Operations related to keys.
- **Members** → `references/resources/Members.md` (23 ops) - Operations related to members.
- **Hooks** → `references/resources/Hooks.md` (21 ops) - Operations related to hooks.
- **SCIM and SAML** → `references/resources/SCIM-and-SAML.md` (20 ops) - Operations related to SCIM and SAML.
- **Resource events** → `references/resources/Resource-events.md` (20 ops) - Operations related to resource events.
- **Vulnerabilities** → `references/resources/Vulnerabilities.md` (20 ops) - Operations related to vulnerabilities.
- **Boards** → `references/resources/Boards.md` (20 ops) - Operations related to boards.
- **Runners** → `references/resources/Runners.md` (19 ops) - Operations related to runners.
- **projects** → `references/resources/projects.md` (18 ops)
- **ai** → `references/resources/ai.md` (18 ops)
- **Terraform** → `references/resources/Terraform.md` (18 ops) - Operations related to terraform.
- **Snippets** → `references/resources/Snippets.md` (18 ops) - Operations related to snippets.
- **Project import** → `references/resources/Project-import.md` (18 ops) - Operations related to project import.
- **Milestones** → `references/resources/Milestones.md` (17 ops) - Operations related to milestones.
- **Personal access tokens** → `references/resources/Personal-access-tokens.md` (16 ops) - Operations related to personal access tokens.
- **Merge request approvals** → `references/resources/Merge-request-approvals.md` (16 ops) - Operations related to merge request approvals.
- **Labels** → `references/resources/Labels.md` (16 ops) - Operations related to labels.
- **Clusters** → `references/resources/Clusters.md` (16 ops) - Operations related to clusters.
- **Issues** → `references/resources/Issues.md` (15 ops) - Operations related to issues.
- **CI variables** → `references/resources/CI-variables.md` (15 ops) - Operations related to CI variables.
- **Releases** → `references/resources/Releases.md` (14 ops) - Operations related to releases.
- **groups** → `references/resources/groups.md` (13 ops)
- **Commits** → `references/resources/Commits.md` (13 ops) - Operations related to commits.
- **Pipelines** → `references/resources/Pipelines.md` (13 ops) - Operations related to pipelines.
- **Licenses** → `references/resources/Licenses.md` (12 ops) - Operations related to licenses.
- **Approval rules** → `references/resources/Approval-rules.md` (12 ops) - Operations related to approval rules.
- **Cluster agents** → `references/resources/Cluster-agents.md` (12 ops) - Operations related to cluster agents.
- **Custom attributes** → `references/resources/Custom-attributes.md` (12 ops) - Operations related to custom attributes.
- **Wikis** → `references/resources/Wikis.md` (12 ops) - Operations related to wikis.
- **Pipeline schedules** → `references/resources/Pipeline-schedules.md` (12 ops) - Operations related to pipeline schedules.
- **Badges** → `references/resources/Badges.md` (12 ops) - Operations related to badges.
- **Protected branches** → `references/resources/Protected-branches.md` (10 ops) - Operations related to protected branches.
- **Protected environments** → `references/resources/Protected-environments.md` (10 ops) - Operations related to protected environments.
- **Repositories** → `references/resources/Repositories.md` (10 ops) - Operations related to repositories.
- **Gitlab pages** → `references/resources/Gitlab-pages.md` (10 ops) - Operations related to gitlab pages.
- **Files** → `references/resources/Files.md` (10 ops) - Operations related to files.
- **Feature flags** → `references/resources/Feature-flags.md` (10 ops) - Operations related to feature flags.
- **Container registry** → `references/resources/Container-registry.md` (9 ops) - Operations related to container registry.
- **Imports** → `references/resources/Imports.md` (9 ops) - Operations related to imports.
- **Namespaces** → `references/resources/Namespaces.md` (8 ops) - Operations related to namespaces.
- **Group credentials inventory** → `references/resources/Group-credentials-inventory.md` (8 ops) - Operations related to group credentials inventory.
- **Provider identities** → `references/resources/Provider-identities.md` (8 ops) - Operations related to provider identities.
- **Push rules** → `references/resources/Push-rules.md` (8 ops) - Operations related to push rules.
- **Templates** → `references/resources/Templates.md` (8 ops) - Operations related to templates.
- **Resource subscriptions** → `references/resources/Resource-subscriptions.md` (8 ops) - Operations related to resource subscriptions.
- **Projects job token scope** → `references/resources/Projects-job-token-scope.md` (8 ops) - Operations related to projects job token scope.
- **Invitations** → `references/resources/Invitations.md` (8 ops) - Operations related to invitations.
- **Environments** → `references/resources/Environments.md` (8 ops) - Operations related to environments.
- **CI jobs** → `references/resources/CI-jobs.md` (8 ops) - Operations related to CI jobs.
- **Job artifacts** → `references/resources/Job-artifacts.md` (8 ops) - Operations related to job artifacts.
- **Branches** → `references/resources/Branches.md` (8 ops) - Operations related to branches.
- **Access requests** → `references/resources/Access-requests.md` (8 ops) - Operations related to access requests.
- **Service accounts** → `references/resources/Service-accounts.md` (7 ops) - Operations related to service accounts.
- **External status checks** → `references/resources/External-status-checks.md` (7 ops) - Operations related to external status checks.
- **Usage data** → `references/resources/Usage-data.md` (7 ops) - Operations related to usage data.
- **Remote mirrors** → `references/resources/Remote-mirrors.md` (7 ops) - Operations related to remote mirrors.
- **Group import and export** → `references/resources/Group-import-and-export.md` (7 ops) - Operations related to group import and export.
- **Draft notes** → `references/resources/Draft-notes.md` (7 ops) - Operations related to draft notes.
- **Jobs** → `references/resources/Jobs.md` (7 ops) - Operations related to jobs.
- **Member roles** → `references/resources/Member-roles.md` (6 ops) - Operations related to member roles.
- **Code search** → `references/resources/Code-search.md` (6 ops) - Operations related to code search.
- **Notification settings** → `references/resources/Notification-settings.md` (6 ops) - Operations related to notification settings.
- **Project topics** → `references/resources/Project-topics.md` (6 ops) - Operations related to project topics.
- **Error tracking** → `references/resources/Error-tracking.md` (6 ops) - Operations related to error tracking.
- **CI triggers** → `references/resources/CI-triggers.md` (6 ops) - Operations related to CI triggers.
- **CI runners** → `references/resources/CI-runners.md` (6 ops) - Operations related to CI runners.
- **Group enterprise users** → `references/resources/Group-enterprise-users.md` (5 ops) - Operations related to group enterprise users.
- **LDAP group links** → `references/resources/LDAP-group-links.md` (5 ops) - Operations related to LDAP group links.
- **Search** → `references/resources/Search.md` (5 ops) - Operations related to search.
- **Active context** → `references/resources/Active-context.md` (5 ops) - Operations related to active context.
- **VSCode** → `references/resources/VSCode.md` (5 ops) - Operations related to VSCode.
- **To-dos** → `references/resources/To-dos.md` (5 ops) - Operations related to to-dos.
- **Instance** → `references/resources/Instance.md` (5 ops) - Operations related to instance.
- **Tags** → `references/resources/Tags.md` (5 ops) - Operations related to tags.
- **hooks** → `references/resources/hooks.md` (5 ops)
- **Project access tokens** → `references/resources/Project-access-tokens.md` (5 ops) - Operations related to project access tokens.
- **Group access tokens** → `references/resources/Group-access-tokens.md` (5 ops) - Operations related to group access tokens.
- **Freeze periods** → `references/resources/Freeze-periods.md` (5 ops) - Operations related to freeze periods.
- **Secure files** → `references/resources/Secure-files.md` (5 ops) - Operations related to secure files.
- **CI resource groups** → `references/resources/CI-resource-groups.md` (5 ops) - Operations related to CI resource groups.
- **Alert management** → `references/resources/Alert-management.md` (5 ops) - Operations related to alert management.
- **Broadcast messages** → `references/resources/Broadcast-messages.md` (5 ops) - Operations related to broadcast messages.
- **code_suggestions** → `references/resources/code-suggestions.md` (4 ops)
- **Analytics** → `references/resources/Analytics.md` (4 ops) - Operations related to analytics.
- **Project alias** → `references/resources/Project-alias.md` (4 ops) - Operations related to project alias.
- **Merge trains** → `references/resources/Merge-trains.md` (4 ops) - Operations related to merge trains.
- **Runner controller tokens** → `references/resources/Runner-controller-tokens.md` (4 ops) - Operations related to runner controller tokens.
- **Runner controllers** → `references/resources/Runner-controllers.md` (4 ops) - Operations related to runner controllers.
- **Data management** → `references/resources/Data-management.md` (4 ops) - Operations related to data management.
- **Support pins** → `references/resources/Support-pins.md` (4 ops) - Operations related to support pins.
- **Impersonation tokens** → `references/resources/Impersonation-tokens.md` (4 ops) - Operations related to impersonation tokens.
- **Avatars** → `references/resources/Avatars.md` (4 ops) - Operations related to avatars.
- **sidekiq** → `references/resources/sidekiq.md` (4 ops)
- **Protected tags** → `references/resources/Protected-tags.md` (4 ops) - Operations related to protected tags.
- **Metric images** → `references/resources/Metric-images.md` (4 ops) - Operations related to metric images.
- **Features** → `references/resources/Features.md` (4 ops) - Operations related to features.
- **Applications** → `references/resources/Applications.md` (4 ops) - Operations related to applications.
- **Batched background migrations** → `references/resources/Batched-background-migrations.md` (4 ops) - Operations related to batched background migration
- **Add on purchases** → `references/resources/Add-on-purchases.md` (3 ops) - Operations related to add on purchases.
- **Software composition analysis** → `references/resources/Software-composition-analysis.md` (3 ops) - Operations related to software composition analysi
- **group_repository_storage_moves** → `references/resources/group-repository-storage-moves.md` (3 ops)
- **Group member roles** → `references/resources/Group-member-roles.md` (3 ops) - Operations related to group member roles.
- **Project mirrors** → `references/resources/Project-mirrors.md` (3 ops) - Operations related to project mirrors.
- **Dependency proxy** → `references/resources/Dependency-proxy.md` (3 ops) - Operations related to dependency proxy.
- **Audit events** → `references/resources/Audit-events.md` (3 ops) - Operations related to audit events.
- **Knowledge graph** → `references/resources/Knowledge-graph.md` (3 ops) - Operations related to knowledge graph.
- **User statuses** → `references/resources/User-statuses.md` (3 ops) - Operations related to user statuses.
- **snippet_repository_storage_moves** → `references/resources/snippet-repository-storage-moves.md` (3 ops)
- **snippets** → `references/resources/snippets.md` (3 ops)
- **project_repository_storage_moves** → `references/resources/project-repository-storage-moves.md` (3 ops)
- **feature_flags** → `references/resources/feature-flags.md` (3 ops)
- **Events** → `references/resources/Events.md` (3 ops) - Operations related to events.
- **offline_exports** → `references/resources/offline-exports.md` (3 ops)
- **Ml model registry** → `references/resources/Ml-model-registry.md` (3 ops) - Operations related to ml model registry.
- **Gitlab subscriptions** → `references/resources/Gitlab-subscriptions.md` (2 ops) - Operations related to gitlab subscriptions.
- **CI minutes** → `references/resources/CI-minutes.md` (2 ops) - Operations related to CI minutes.
- **dependency_list_exports** → `references/resources/dependency-list-exports.md` (2 ops)
- **Iterations** → `references/resources/Iterations.md` (2 ops) - Operations related to iterations.
- **Dependency management** → `references/resources/Dependency-management.md` (2 ops) - Operations related to dependency management.
- **Project Google Cloud integration** → `references/resources/Project-Google-Cloud-integration.md` (2 ops) - Operations related to project Google Cloud integra
- **Project approvals** → `references/resources/Project-approvals.md` (2 ops) - Operations related to project approvals.
- **Workspaces** → `references/resources/Workspaces.md` (2 ops) - Operations related to workspaces.
- **LDAP groups** → `references/resources/LDAP-groups.md` (2 ops) - Operations related to LDAP groups.
- **Advanced search rollout** → `references/resources/Advanced-search-rollout.md` (2 ops) - Operations related to advanced search rollout.
- **DORA metrics** → `references/resources/DORA-metrics.md` (2 ops) - Operations related to DORA metrics.
- **Compliance policy settings** → `references/resources/Compliance-policy-settings.md` (2 ops) - Operations related to compliance policy settings.
- **mcp** → `references/resources/mcp.md` (2 ops)
- **Unleash** → `references/resources/Unleash.md` (2 ops) - Operations related to unleash.
- **Attestations** → `references/resources/Attestations.md` (2 ops) - Operations related to attestations.
- **Suggestions** → `references/resources/Suggestions.md` (2 ops) - Operations related to suggestions.
- **Project templates** → `references/resources/Project-templates.md` (2 ops) - Operations related to project templates.
- **Metadata** → `references/resources/Metadata.md` (2 ops) - Operations related to metadata.
- **CI lint** → `references/resources/CI-lint.md` (2 ops) - Operations related to CI lint.
- **integrations** → `references/resources/integrations.md` (2 ops)
- **Commit statuses** → `references/resources/Commit-statuses.md` (2 ops) - Operations related to commit statuses.
- **Admin** → `references/resources/Admin.md` (2 ops) - Operations related to admin.
- **Plan limits** → `references/resources/Plan-limits.md` (2 ops) - Operations related to plan limits.
- **swagger_doc** → `references/resources/swagger-doc.md` (2 ops)
- **Security scans** → `references/resources/Security-scans.md` (1 ops) - Operations related to security scans.
- **duo_code_review** → `references/resources/duo-code-review.md` (1 ops)
- **chat** → `references/resources/chat.md` (1 ops)
- **pipelines** → `references/resources/pipelines.md` (1 ops)
- **Code review analytics** → `references/resources/Code-review-analytics.md` (1 ops) - Operations related to code review analytics.
- **OAuth applications** → `references/resources/OAuth-applications.md` (1 ops) - Operations related to OAuth applications.
- **Experiments** → `references/resources/Experiments.md` (1 ops) - Operations related to experiments.
- **Ai catalog** → `references/resources/Ai-catalog.md` (1 ops) - Operations related to ai catalog.
- **admin** → `references/resources/admin.md` (1 ops)
- **Web commits** → `references/resources/Web-commits.md` (1 ops) - Operations related to web commits.
- **User** → `references/resources/User.md` (1 ops) - Operations related to user.
- **Metrics** → `references/resources/Metrics.md` (1 ops) - Operations related to metrics.
- **Submodules** → `references/resources/Submodules.md` (1 ops) - Operations related to submodules.
- **Project snapshots** → `references/resources/Project-snapshots.md` (1 ops) - Operations related to project snapshots.
- **Organizations** → `references/resources/Organizations.md` (1 ops) - Operations related to organizations.
- **Markdown** → `references/resources/Markdown.md` (1 ops) - Operations related to markdown.
- **Jira connect subscriptions** → `references/resources/Jira-connect-subscriptions.md` (1 ops) - Operations related to jira connect subscriptions.
- **GLQL** → `references/resources/GLQL.md` (1 ops) - Operations related to GLQL.
- **Agents** → `references/resources/Agents.md` (1 ops) - Operations related to agents.
- **LDAP** → `references/resources/LDAP.md` (1 ops) - Operations related to LDAP.
- **Group** → `references/resources/Group.md` (1 ops) - Operations related to group.
- **CI catalog** → `references/resources/CI-catalog.md` (1 ops) - Operations related to CI catalog.
- **Migrations** → `references/resources/Migrations.md` (1 ops) - Operations related to migrations.
- **Database dictionary** → `references/resources/Database-dictionary.md` (1 ops) - Operations related to database dictionary.
