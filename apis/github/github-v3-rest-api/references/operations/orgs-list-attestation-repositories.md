# GET /orgs/{org}/attestations/repositories

**Resource:** [orgs](../resources/orgs.md)
**List attestation repositories**
**Operation ID:** `orgs/list-attestation-repositories`

List repositories owned by the provided organization that have created at least one attested artifact
Results will be sorted in ascending order by repository ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `predicate_type` | query | string | No | Optional filter for fetching attestations with a given predicate type.
This option accepts `provenance`, `sbom`, `release`, or freeform text
for custom predicate types. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

