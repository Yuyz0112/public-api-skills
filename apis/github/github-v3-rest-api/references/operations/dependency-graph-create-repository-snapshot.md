# POST /repos/{owner}/{repo}/dependency-graph/snapshots

**Resource:** [dependency-graph](../resources/dependency-graph.md)
**Create a snapshot of dependencies for a repository**
**Operation ID:** `dependency-graph/create-repository-snapshot`

Create a new snapshot of a repository's dependencies.

The authenticated user must have access to the repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [snapshot](../schemas/snapshot/snapshot.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

