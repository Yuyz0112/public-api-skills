# GET /api/v4/projects/{id}/google_cloud/setup/integrations.sh

**Resource:** [Project Google Cloud integration](../resources/Project-Google-Cloud-integration.md)
**Get shell script to setup an integration in Google Cloud**
**Operation ID:** `getApiV4ProjectsIdGoogleCloudSetupIntegrationsSh`

This feature is experimental.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `enable_google_cloud_artifact_registry` | query | boolean | No | If `true`, indicates the Google Artifact Management integration should be enabled |
| `google_cloud_artifact_registry_project_id` | query | string | No | Google Cloud Project ID for the Artifact Registry |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

