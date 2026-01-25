# POST /orgs/{org}/artifacts/metadata/deployment-record/cluster/{cluster}

**Resource:** [orgs](../resources/orgs.md)
**Set cluster deployment records**
**Operation ID:** `orgs/set-cluster-deployment-records`

Set deployment records for a given cluster.
If proposed records in the 'deployments' field have identical 'cluster', 'logical_environment',
'physical_environment', and 'deployment_name' values as existing records, the existing records will be updated.
If no existing records match, new records will be created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster` | path | string | Yes | The cluster name. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deployment records created or updated successfully.
 |

