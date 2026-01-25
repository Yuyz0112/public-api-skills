# GET /repos/{owner}/{repo}/dependency-graph/sbom

**Resource:** [dependency-graph](../resources/dependency-graph.md)
**Export a software bill of materials (SBOM) for a repository.**
**Operation ID:** `dependency-graph/export-sbom`

Exports the software bill of materials (SBOM) for a repository in SPDX JSON format.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dependency-graph-spdx-sbom](../schemas/dependency-graph-spdx-sbom/dependency-graph-spdx-sbom.md)

