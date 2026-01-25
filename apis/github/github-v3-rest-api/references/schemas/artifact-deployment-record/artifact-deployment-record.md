# artifact-deployment-record

Artifact Metadata Deployment Record

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `digest` | string | No |  |
| `logical_environment` | string | No |  |
| `physical_environment` | string | No |  |
| `cluster` | string | No |  |
| `deployment_name` | string | No |  |
| `tags` | object | No |  |
| `runtime_risks` | string[] | No | A list of runtime risks associated with the deployment. |
| `created_at` | string | No |  |
| `updated_at` | string | No |  |
| `attestation_id` | integer | No | The ID of the provenance attestation associated with the deployment record. |

