# GET /api/v4/groups/{id}/ssh_certificates

**Resource:** [Keys](../resources/Keys.md)
**Get a list of ssh certificates created for a group.**
**Operation ID:** `getApiV4GroupsIdSshCertificates`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | 404 Not Found |

**Success Response Schema:**

[APIEntitiesSshCertificate](../schemas/APIEntitiesSshCertificate/APIEntitiesSshCertificate.md)

