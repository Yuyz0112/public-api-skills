# cc_PublicApplication

Provides the current state and configuration of a Containers application.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | [cc_ISO8601Timestamp](cc-ISO8601Timestamp.md) | Yes |  |
| `durable_object` | [cc_DurableObjectsConfigurationNamespaceId](cc-DurableObjectsConfigurationNamespaceId.md) | No |  |
| `health` | [cc_ApplicationHealthInstances](cc-ApplicationHealthInstances.md) | Yes |  |
| `id` | [cc_ApplicationID](cc-ApplicationID.md) | Yes |  |
| `image` | [cc_Image](cc-Image.md) | Yes |  |
| `instance_type` | [cc_PublicInstanceType](cc-PublicInstanceType.md) | Yes |  |
| `max_instances` | integer | Yes | Maximum number of instances that the application will allow. |
| `name` | string | Yes | The name of the application. |
| `observability` | [cc_Observability](cc-Observability.md) | No |  |
| `rollout_active_grace_period` | [cc_ApplicationRolloutActiveGracePeriod](cc-ApplicationRolloutActiveGracePeriod.md) | No |  |
| `updated_at` | [cc_ISO8601Timestamp](cc-ISO8601Timestamp.md) | Yes |  |
| `version` | integer | Yes | The current version number of this application. This increments with application rollouts. |

