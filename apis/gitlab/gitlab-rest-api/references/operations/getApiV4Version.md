# GET /api/v4/version

**Resource:** [Metadata](../resources/Metadata.md)
**Retrieves version information for the GitLab instance**
**Operation ID:** `getApiV4Version`

This feature was introduced in GitLab 8.13 and deprecated in 15.5. We recommend you instead use the Metadata API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesMetadata](../schemas/APIEntitiesMetadata/APIEntitiesMetadata.md)

