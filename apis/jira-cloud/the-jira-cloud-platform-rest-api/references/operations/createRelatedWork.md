# POST /rest/api/3/version/{id}/relatedwork

**Resource:** [Project versions](../resources/Project-versions.md)
**Create related work**
**Operation ID:** `createRelatedWork`

Creates a related work for the given version. You can only create a generic link type of related works via this API. relatedWorkId will be auto-generated UUID, that does not need to be provided.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Resolve issues:* and *Edit issues* [Managing project permissions](https://confluence.atlassian.com/adminjiraserver/managing-project-permissions-938847145.html) for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [VersionRelatedWork](../schemas/Version/VersionRelatedWork.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the version is not found. |

**Success Response Schema:**

[VersionRelatedWork](../schemas/Version/VersionRelatedWork.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
