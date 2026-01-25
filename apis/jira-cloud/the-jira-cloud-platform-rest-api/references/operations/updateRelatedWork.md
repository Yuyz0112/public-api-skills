# PUT /rest/api/3/version/{id}/relatedwork

**Resource:** [Project versions](../resources/Project-versions.md)
**Update related work**
**Operation ID:** `updateRelatedWork`

Updates the given related work. You can only update generic link related works via Rest APIs. Any archived version related works can't be edited.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Resolve issues:* and *Edit issues* [Managing project permissions](https://confluence.atlassian.com/adminjiraserver/managing-project-permissions-938847145.html) for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version to update the related work on. For the related work id, pass it to the input JSON. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [VersionRelatedWork](../schemas/Version/VersionRelatedWork.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful together with updated related work. |
| 400 | Returned if the request data is invalid |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the version or the related work is not found. |

**Success Response Schema:**

[VersionRelatedWork](../schemas/Version/VersionRelatedWork.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
