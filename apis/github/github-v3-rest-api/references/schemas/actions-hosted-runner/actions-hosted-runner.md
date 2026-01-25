# actions-hosted-runner

A Github-hosted hosted runner.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier of the hosted runner. |
| `name` | string | Yes | The name of the hosted runner. |
| `runner_group_id` | integer | No | The unique identifier of the group that the hosted runner belongs to. |
| `image_details` | [nullable-actions-hosted-runner-pool-image](nullable-actions-hosted-runner-pool-image.md) | Yes |  |
| `machine_size_details` | [actions-hosted-runner-machine-spec](actions-hosted-runner-machine-spec.md) | Yes |  |
| `status` | enum: Ready, Provisioning, Shutdown... | Yes | The status of the runner. |
| `platform` | string | Yes | The operating system of the image. |
| `maximum_runners` | integer | No | The maximum amount of hosted runners. Runners will not scale automatically above this number. Use this setting to limit your cost. |
| `public_ip_enabled` | boolean | Yes | Whether public IP is enabled for the hosted runners. |
| `public_ips` | public-ip[] | No | The public IP ranges when public IP is enabled for the hosted runners. |
| `last_active_on` | string (date-time) | No | The time at which the runner was last used, in ISO 8601 format. |
| `image_gen` | boolean | No | Whether custom image generation is enabled for the hosted runners. |

