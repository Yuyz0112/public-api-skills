# POST /tasks/{task_gid}/stories

**Resource:** [Stories](../resources/Stories.md)
**Create a story on a task**
**Operation ID:** `createStoryForTask`

<b>Required scope: </b><code>stories:write</code>

Adds a story to a task. This endpoint currently only allows for comment
stories to be created. The comment will be authored by the currently
authenticated user, and timestamped when the server receives the request.

Returns the full record for the new story added to the task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The story to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a new story. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: stories:write
