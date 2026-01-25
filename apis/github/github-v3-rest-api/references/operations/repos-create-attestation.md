# POST /repos/{owner}/{repo}/attestations

**Resource:** [repos](../resources/repos.md)
**Create an attestation**
**Operation ID:** `repos/create-attestation`

Store an artifact attestation and associate it with a repository.

The authenticated user must have write permission to the repository and, if using a fine-grained access token, the `attestations:write` permission is required.

Artifact attestations are meant to be created using the [attest action](https://github.com/actions/attest). For more information, see our guide on [using artifact attestations to establish a build's provenance](https://docs.github.com/actions/security-guides/using-artifact-attestations-to-establish-provenance-for-builds).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | response |
| 403 | (reference) |
| 422 | (reference) |

