# DELETE /api/v4/projects/{id}/environments/review_apps

**Resource:** [Environments](../resources/Environments.md)
**Delete multiple stopped review apps**
**Operation ID:** `deleteApiV4ProjectsIdEnvironmentsReviewApps`

It schedules for deletion multiple environments that have already been stopped and are in the review app folder. The actual deletion is performed after 1 week from the time of execution. By default, it only deletes environments 30 days or older. You can change this default using the `before` parameter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `before` | query | Time | No | The date before which environments can be deleted. Defaults to 30 days ago. Expected in ISO 8601 format (`YYYY-MM-DDTHH:MM:SSZ`) |
| `limit` | query | integer | No | Maximum number of environments to delete. Defaults to 100 |
| `dry_run` | query | boolean | No | Defaults to true for safety reasons. It performs a dry run where no actual deletion will be performed. Set to false to actually delete the environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |
| 409 | Conflict |

