# GET /repos/{owner}/{repo}/collaborators/{username}/permission

**Resource:** [repos](../resources/repos.md)
**Get repository permissions for a user**
**Operation ID:** `repos/get-collaborator-permission-level`

Checks the repository permission and role of a collaborator.

The `permission` attribute provides the legacy base roles of `admin`, `write`, `read`, and `none`, where the
`maintain` role is mapped to `write` and the `triage` role is mapped to `read`.
The `role_name` attribute provides the name of the assigned role, including custom roles. The
`permission` can also be used to determine which base level of access the collaborator has to the repository.

The calculated permissions are the highest role assigned to the collaborator after considering all sources of grants, including: repo, teams, organization, and enterprise.
There is presently not a way to differentiate between an organization level grant and a repository level grant from this endpoint response.

## Responses

| Status | Description |
|--------|-------------|
| 200 | if user has admin permissions |
| 404 | (reference) |

**Success Response Schema:**

[repository-collaborator-permission](../schemas/repository-collaborator-permission/repository-collaborator-permission.md)

