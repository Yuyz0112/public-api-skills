# GET /api/v4/projects/{id}/attestations/{subject_digest}

**Resource:** [Attestations](../resources/Attestations.md)
**Fetch the list of all attestations for a specific project and artifact hash**
**Operation ID:** `getApiV4ProjectsIdAttestationsSubjectDigest`

This feature was introduced in GitLab 18.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `subject_digest` | path | string | Yes | The SHA-256 hash of the artifact |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Artifact SHA-256 not found |

**Success Response Schema:**

[APIEntitiesSupplyChainAttestation](../schemas/APIEntitiesSupplyChainAttestation/APIEntitiesSupplyChainAttestation.md)

