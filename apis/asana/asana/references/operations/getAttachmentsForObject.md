# GET /attachments

**Resource:** [Attachments](../resources/Attachments.md)
**Get attachments from an object**
**Operation ID:** `getAttachmentsForObject`

<b>Required scope: </b><code>attachments:read</code>

Returns the compact records for all attachments on the object.
There are three possible `parent` values for this request: `project`, `project_brief`, and `task`. For a project, an attachment refers to a file uploaded to the "Key resources" section in the project Overview. For a project brief, an attachment refers to inline files in the project brief itself. For a task, an attachment refers to a file directly associated to that task.

Note that within the Asana app, inline images in the task description do not appear in the index of image thumbnails nor as stories in the task. However, requests made to `GET /attachments` for a task will return all of the images in the task, including inline images.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | Yes | Globally unique identifier for object to fetch statuses from. Must be a GID for a `project`, `project_brief`, or `task`. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified object's attachments. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: attachments:read
