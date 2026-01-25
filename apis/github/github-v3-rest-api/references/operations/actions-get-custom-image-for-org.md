# GET /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}

**Resource:** [actions](../resources/actions.md)
**Get a custom image definition for GitHub Actions Hosted Runners**
**Operation ID:** `actions/get-custom-image-for-org`

Get a custom image definition for GitHub Actions Hosted Runners.

OAuth tokens and personal access tokens (classic) need the `manage_runners:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-hosted-runner-custom-image](../schemas/actions-hosted-runner-custom-image/actions-hosted-runner-custom-image.md)

