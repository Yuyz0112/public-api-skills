# FoundGroup

A group found in a search.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatarUrl` | string | No | Avatar url for the group/team if present. |
| `groupId` | string | No | The ID of the group, which uniquely identifies the group across all Atlassian products. For example, *952d12c3-5b5b-4d04-bb32-44d383afc4b2*. |
| `html` | string | No | The group name with the matched query string highlighted with the HTML bold tag. |
| `labels` | GroupLabel[] | No |  |
| `managedBy` | enum: EXTERNAL, ADMINS, TEAM_MEMBERS... | No | Describes who/how the team is managed. The possible values are  
\* external - when team is synced from an external directory like SCIM or HRIS, and team members cannot be modified.  
\* admins - when a team is managed by an admin (team members can only be modified by admins).  
\* team-members - managed by existing team members, new members need to be invited to join.  
\* open - anyone can join or modify this team. |
| `name` | string | No | The name of the group. The name of a group is mutable, to reliably identify a group use ``groupId`.` |
| `usageType` | enum: USERBASE_GROUP, TEAM_COLLABORATION, ADMIN_OVERSIGHT | No | Describes the type of group. The possible values are  
\* team-collaboration - A platform team managed in people directory.  
\* userbase-group - a group of users created in adminhub.  
\* admin-oversight - currently unused. |

