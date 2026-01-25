# GET /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions/{version}

**Resource:** [actions](../resources/actions.md)
**Get an image version of a custom image for GitHub Actions Hosted Runners**
**Operation ID:** `actions/get-custom-image-version-for-org`

Get an image version of a custom image for GitHub Actions Hosted Runners.

OAuth tokens and personal access tokens (classic) need the `manage_runners:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-hosted-runner-custom-image-version](../schemas/actions-hosted-runner-custom-image-version/actions-hosted-runner-custom-image-version.md)

