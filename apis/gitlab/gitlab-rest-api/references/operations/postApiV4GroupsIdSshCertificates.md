# POST /api/v4/groups/{id}/ssh_certificates

**Resource:** [Keys](../resources/Keys.md)
**Create a ssh certificate for a group.**
**Operation ID:** `postApiV4GroupsIdSshCertificates`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesSshCertificate](../schemas/APIEntitiesSshCertificate/APIEntitiesSshCertificate.md)

