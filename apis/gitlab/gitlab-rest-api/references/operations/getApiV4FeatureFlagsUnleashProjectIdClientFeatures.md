# GET /api/v4/feature_flags/unleash/{project_id}/client/features

**Resource:** [Unleash](../resources/Unleash.md)
**Get a list of features**
**Operation ID:** `getApiV4FeatureFlagsUnleashProjectIdClientFeatures`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | string | Yes | The ID of a project |
| `instance_id` | query | string | No | The instance ID of Unleash Client |
| `app_name` | query | string | No | The application name of Unleash Client |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

