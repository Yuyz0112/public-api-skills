# GET /api/v4/projects/{id}/attestations/{attestation_iid}/download

**Resource:** [Attestations](../resources/Attestations.md)
**Fetch a specific bundle by iid**
**Operation ID:** `getApiV4ProjectsIdAttestationsAttestationIidDownload`

This feature was introduced in GitLab 18.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `attestation_iid` | path | any | Yes | The iid of the attestation |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Artifact SHA-256 not found |

