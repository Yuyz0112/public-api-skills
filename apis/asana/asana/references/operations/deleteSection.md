# DELETE /sections/{section_gid}

**Resource:** [Sections](../resources/Sections.md)
**Delete a section**
**Operation ID:** `deleteSection`

A specific, existing section can be deleted by making a DELETE request on
the URL for that section.

Note that sections must be empty to be deleted.

The last remaining section cannot be deleted.

Returns an empty data block.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified section. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
