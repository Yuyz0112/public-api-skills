# POST /api/v4/organizations

**Resource:** [Organizations](../resources/Organizations.md)
**Create an organization**
**Operation ID:** `postApiV4Organizations`

This feature was introduced in GitLab 17.5. \
                    This feature is currently in an experimental state. \
                    This feature is behind the `allow_organization_creation` feature flag. \
                    In GitLab 18.3, feature flag changed to `organization_switching`.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesOrganizationsOrganization](../schemas/APIEntitiesOrganizationsOrganization/APIEntitiesOrganizationsOrganization.md)

