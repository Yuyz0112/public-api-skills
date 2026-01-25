# POST /orgs/{org}/artifacts/metadata/storage-record

**Resource:** [orgs](../resources/orgs.md)
**Create artifact metadata storage record**
**Operation ID:** `orgs/create-artifact-storage-record`

Create metadata storage records for artifacts associated with an organization.
This endpoint will create a new artifact storage record on behalf of any artifact matching the provided digest and
associated with a repository owned by the organization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Artifact metadata storage record stored successfully. |

