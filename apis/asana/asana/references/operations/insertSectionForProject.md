# POST /projects/{project_gid}/sections/insert

**Resource:** [Sections](../resources/Sections.md)
**Move or Insert sections**
**Operation ID:** `insertSectionForProject`

Move sections relative to each other. One of
`before_section` or `after_section` is required.

Sections cannot be moved between projects.

Returns an empty data block.

## Request Body

The section's move action.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully moved the specified section. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
