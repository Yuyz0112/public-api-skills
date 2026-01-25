# GET /orgs/{org}/artifacts/{subject_digest}/metadata/storage-records

**Resource:** [orgs](../resources/orgs.md)
**List artifact storage records**
**Operation ID:** `orgs/list-artifact-storage-records`

List a collection of artifact storage records with a given subject digest that are associated with repositories owned by an organization.

The collection of storage records returned by this endpoint is filtered according to the authenticated user's permissions; if the authenticated user cannot read a repository, the attestations associated with that repository will not be included in the response. In addition, when using a fine-grained access token the `content:read` permission is required.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subject_digest` | path | string | Yes | The parameter should be set to the attestation's subject's SHA256 digest, in the form `sha256:HEX_DIGEST`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

