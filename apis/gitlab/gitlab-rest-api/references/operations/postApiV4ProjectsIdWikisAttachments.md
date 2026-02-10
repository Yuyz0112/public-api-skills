# POST /api/v4/projects/{id}/wikis/attachments

**Resource:** [Wikis](../resources/Wikis.md)
**Upload an attachment to the wiki repository**
**Operation ID:** `postApiV4ProjectsIdWikisAttachments`

This feature was introduced in GitLab 11.3.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesWikiAttachment](../schemas/APIEntitiesWikiAttachment/APIEntitiesWikiAttachment.md)

