---
name: github-v3-rest-api
description: GitHub's v3 REST API.. Use when working with the GitHub v3 REST API or when the user needs to interact with this API.
license: MIT (https://spdx.org/licenses/MIT)
metadata:
  api-version: "1.1.4"
  openapi-version: "3.0.3"
---

# GitHub v3 REST API

GitHub's v3 REST API.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 43 resource index files
├── operations/     # 1078 operation detail files
└── schemas/        # 860 schema groups, 904 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.github.com`

## Resources

- **repos** → `references/resources/repos.md` (204 ops) - Interact with GitHub Repos.
- **actions** → `references/resources/actions.md` (184 ops) - Endpoints to manage GitHub Actions using the REST 
- **orgs** → `references/resources/orgs.md` (104 ops) - Interact with organizations.
- **issues** → `references/resources/issues.md` (49 ops) - Interact with GitHub Issues.
- **codespaces** → `references/resources/codespaces.md` (48 ops) - Endpoints to manage Codespaces using the REST API.
- **users** → `references/resources/users.md` (47 ops) - Interact with and view information about users and
- **apps** → `references/resources/apps.md` (37 ops) - Information for integrations and installations.
- **activity** → `references/resources/activity.md` (32 ops) - Activity APIs provide access to notifications, sub
- **teams** → `references/resources/teams.md` (32 ops) - Interact with GitHub Teams.
- **packages** → `references/resources/packages.md` (27 ops) - Manage packages for authenticated users and organi
- **pulls** → `references/resources/pulls.md` (27 ops) - Interact with GitHub Pull Requests.
- **projects** → `references/resources/projects.md` (26 ops) - Endpoints to manage Projects using the REST API.
- **dependabot** → `references/resources/dependabot.md` (22 ops) - Endpoints to manage Dependabot.
- **migrations** → `references/resources/migrations.md` (22 ops) - Move projects to or from GitHub.
- **code-scanning** → `references/resources/code-scanning.md` (21 ops) - Retrieve code scanning alerts from a repository.
- **code-security** → `references/resources/code-security.md` (20 ops) - Endpoints to manage Code security using the REST A
- **gists** → `references/resources/gists.md` (20 ops) - View, modify your gists.
- **reactions** → `references/resources/reactions.md` (15 ops) - Interact with reactions to various GitHub entities
- **git** → `references/resources/git.md` (13 ops) - Raw Git functionality.
- **checks** → `references/resources/checks.md` (12 ops) - Rich interactions with checks run by your integrat
- **security-advisories** → `references/resources/security-advisories.md` (10 ops) - Manage security advisories.
- **billing** → `references/resources/billing.md` (10 ops) - Monitor charges and usage from Actions and Package
- **copilot** → `references/resources/copilot.md` (9 ops) - Endpoints to manage Copilot using the REST API.
- **interactions** → `references/resources/interactions.md` (9 ops) - Owner or admin management of users interactions.
- **secret-scanning** → `references/resources/secret-scanning.md` (9 ops) - Retrieve secret scanning alerts from a repository.
- **search** → `references/resources/search.md` (7 ops) - Search for specific items on GitHub.
- **classroom** → `references/resources/classroom.md` (6 ops) - Interact with GitHub Classroom.
- **enterprise-team-memberships** → `references/resources/enterprise-team-memberships.md` (6 ops) - Endpoints to manage GitHub Enterprise Team members
- **enterprise-team-organizations** → `references/resources/enterprise-team-organizations.md` (6 ops) - Endpoints to manage GitHub Enterprise Team organiz
- **private-registries** → `references/resources/private-registries.md` (6 ops) - Manage private registry configurations.
- **hosted-compute** → `references/resources/hosted-compute.md` (6 ops) - Manage hosted compute networking resources.
- **meta** → `references/resources/meta.md` (5 ops) - Endpoints that give information about the API.
- **enterprise-teams** → `references/resources/enterprise-teams.md` (5 ops) - Endpoints to manage GitHub Enterprise Teams.
- **campaigns** → `references/resources/campaigns.md` (5 ops) - Endpoints to manage campaigns via the REST API.
- **licenses** → `references/resources/licenses.md` (3 ops) - View various OSS licenses.
- **dependency-graph** → `references/resources/dependency-graph.md` (3 ops) - Endpoints to access Dependency Graph features.
- **codes-of-conduct** → `references/resources/codes-of-conduct.md` (2 ops) - Insight into codes of conduct for your communities
- **gitignore** → `references/resources/gitignore.md` (2 ops) - View gitignore templates
- **markdown** → `references/resources/markdown.md` (2 ops) - Render GitHub flavored Markdown
- **oidc** → `references/resources/oidc.md` (2 ops) - Endpoints to manage GitHub OIDC configuration usin
- **credentials** → `references/resources/credentials.md` (1 ops) - Revoke compromised or leaked GitHub credentials.
- **emojis** → `references/resources/emojis.md` (1 ops) - List emojis available to use on GitHub.
- **rate-limit** → `references/resources/rate-limit.md` (1 ops) - Check your current rate limit status.
