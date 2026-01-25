# GET /repos/{owner}/{repo}/attestations/{subject_digest}

**Resource:** [repos](../resources/repos.md)
**List attestations**
**Operation ID:** `repos/list-attestations`

List a collection of artifact attestations with a given subject digest that are associated with a repository.

The authenticated user making the request must have read access to the repository. In addition, when using a fine-grained access token the `attestations:read` permission is required.

**Please note:** in order to offer meaningful security benefits, an attestation's signature and timestamps **must** be cryptographically verified, and the identity of the attestation signer **must** be validated. Attestations can be verified using the [GitHub CLI `attestation verify` command](https://cli.github.com/manual/gh_attestation_verify). For more information, see [our guide on how to use artifact attestations to establish a build's provenance](https://docs.github.com/actions/security-guides/using-artifact-attestations-to-establish-provenance-for-builds).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subject_digest` | path | string | Yes | The parameter should be set to the attestation's subject's SHA256 digest, in the form `sha256:HEX_DIGEST`. |
| `predicate_type` | query | string | No | Optional filter for fetching attestations with a given predicate type.
This option accepts `provenance`, `sbom`, `release`, or freeform text
for custom predicate types. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

