# PUT /api/v4/projects/{id}/pages/domains/{domain}/verify

**Resource:** [Gitlab pages](../resources/Gitlab-pages.md)
**Verify a pages domain**
**Operation ID:** `putApiV4ProjectsIdPagesDomainsDomainVerify`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `domain` | path | string | Yes | The domain to verify |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesPagesDomain](../schemas/APIEntitiesPagesDomain/APIEntitiesPagesDomain.md)

