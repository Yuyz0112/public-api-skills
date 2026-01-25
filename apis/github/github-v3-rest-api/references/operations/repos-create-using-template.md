# POST /repos/{template_owner}/{template_repo}/generate

**Resource:** [repos](../resources/repos.md)
**Create a repository using a template**
**Operation ID:** `repos/create-using-template`

Creates a new repository using a repository template. Use the `template_owner` and `template_repo` route parameters to specify the repository to use as the template. If the repository is not public, the authenticated user must own or be a member of an organization that owns the repository. To check if a repository is available to use as a template, get the repository's information using the [Get a repository](https://docs.github.com/rest/repos/repos#get-a-repository) endpoint and check that the `is_template` key is `true`.

OAuth app tokens and personal access tokens (classic) need the `public_repo` or `repo` scope to create a public repository, and `repo` scope to create a private repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `template_owner` | path | string | Yes | The account owner of the template repository. The name is not case sensitive. |
| `template_repo` | path | string | Yes | The name of the template repository without the `.git` extension. The name is not case sensitive. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[full-repository](../schemas/full-repository/full-repository.md)

