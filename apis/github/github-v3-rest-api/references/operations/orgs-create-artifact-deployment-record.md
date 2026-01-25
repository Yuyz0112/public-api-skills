# POST /orgs/{org}/artifacts/metadata/deployment-record

**Resource:** [orgs](../resources/orgs.md)
**Create an artifact deployment record**
**Operation ID:** `orgs/create-artifact-deployment-record`

Create or update deployment records for an artifact associated with an organization.
This endpoint allows you to record information about a specific artifact, such as its name, digest, environments, cluster, and deployment.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Artifact deployment record stored successfully. |

