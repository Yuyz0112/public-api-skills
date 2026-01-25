# dependency-graph

Endpoints to access Dependency Graph features.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/repos/{owner}/{repo}/dependency-graph/compare/{basehead}` | Get a diff of the dependencies between commits | [View](../operations/dependency-graph-diff-range.md) |
| GET | `/repos/{owner}/{repo}/dependency-graph/sbom` | Export a software bill of materials (SBOM) for a repository. | [View](../operations/dependency-graph-export-sbom.md) |
| POST | `/repos/{owner}/{repo}/dependency-graph/snapshots` | Create a snapshot of dependencies for a repository | [View](../operations/dependency-graph-create-repository-snapshot.md) |
