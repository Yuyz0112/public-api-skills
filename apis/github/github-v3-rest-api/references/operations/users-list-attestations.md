# GET /users/{username}/attestations/{subject_digest}

**Resource:** [users](../resources/users.md)
**List attestations**
**Operation ID:** `users/list-attestations`

List a collection of artifact attestations with a given subject digest that are associated with repositories owned by a user.

The collection of attestations returned by this endpoint is filtered according to the authenticated user's permissions; if the authenticated user cannot read a repository, the attestations associated with that repository will not be included in the response. In addition, when using a fine-grained access token the `attestations:read` permission is required.

**Please note:** in order to offer meaningful security benefits, an attestation's signature and timestamps **must** be cryptographically verified, and the identity of the attestation signer **must** be validated. Attestations can be verified using the [GitHub CLI `attestation verify` command](https://cli.github.com/manual/gh_attestation_verify). For more information, see [our guide on how to use artifact attestations to establish a build's provenance](https://docs.github.com/actions/security-guides/using-artifact-attestations-to-establish-provenance-for-builds).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subject_digest` | path | string | Yes | Subject Digest |
| `predicate_type` | query | string | No | Optional filter for fetching attestations with a given predicate type.
This option accepts `provenance`, `sbom`, `release`, or freeform text
for custom predicate types. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 201 | Response |
| 204 | Response |
| 404 | (reference) |

