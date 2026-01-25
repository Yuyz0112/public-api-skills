# GET /stories/{story_gid}

**Resource:** [Stories](../resources/Stories.md)
**Get a story**
**Operation ID:** `getStory`

<b>Required scope: </b><code>stories:read</code>

<table>
  <tr>
    <th>Field</th>
    <th>Required Scope</th>
  </tr>
  <tr>
    <td><code>previews</code></td>
    <td><code>attachments:read</code></td>
  </tr>
  <tr>
    <td><code>attachments</code></td>
    <td><code>attachments:read</code></td>
  </tr>
</table>

Returns the full record for a single story.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified story. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: stories:read
