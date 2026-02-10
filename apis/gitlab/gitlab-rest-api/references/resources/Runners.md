# Runners

Operations related to runners.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/runner_controllers/{runner_controller_id}/tokens` | List runner controller tokens | [View](../operations/getApiV4RunnerControllersRunnerControllerIdTokens.md) |
| GET | `/api/v4/runner_controllers` | List runner controllers | [View](../operations/getApiV4RunnerControllers.md) |
| POST | `/api/v4/user/runners` | Create a runner owned by currently authenticated user | [View](../operations/postApiV4UserRunners.md) |
| GET | `/api/v4/runners` | Get runners available for user | [View](../operations/getApiV4Runners.md) |
| GET | `/api/v4/runners/all` | Get all runners - shared and project | [View](../operations/getApiV4RunnersAll.md) |
| GET | `/api/v4/runners/{id}` | Get runner's details | [View](../operations/getApiV4RunnersId.md) |
| PUT | `/api/v4/runners/{id}` | Update runner's details | [View](../operations/putApiV4RunnersId.md) |
| DELETE | `/api/v4/runners/{id}` | Remove a runner | [View](../operations/deleteApiV4RunnersId.md) |
| GET | `/api/v4/runners/{id}/managers` | Get a list of all runner's managers | [View](../operations/getApiV4RunnersIdManagers.md) |
| GET | `/api/v4/runners/{id}/projects` | Get projects associated with a runner | [View](../operations/getApiV4RunnersIdProjects.md) |
| GET | `/api/v4/runners/{id}/jobs` | List jobs running on a runner | [View](../operations/getApiV4RunnersIdJobs.md) |
| POST | `/api/v4/runners/{id}/reset_authentication_token` | Reset runner authentication token | [View](../operations/postApiV4RunnersIdResetAuthenticationToken.md) |
| GET | `/api/v4/projects/{id}/runners` | Get runners available for project | [View](../operations/getApiV4ProjectsIdRunners.md) |
| POST | `/api/v4/projects/{id}/runners` | Assign a runner to project | [View](../operations/postApiV4ProjectsIdRunners.md) |
| DELETE | `/api/v4/projects/{id}/runners/{runner_id}` | Unassign a runner from project | [View](../operations/deleteApiV4ProjectsIdRunnersRunnerId.md) |
| GET | `/api/v4/groups/{id}/runners` | Get runners available for group | [View](../operations/getApiV4GroupsIdRunners.md) |
| POST | `/api/v4/runners/reset_registration_token` | Reset runner registration token | [View](../operations/postApiV4RunnersResetRegistrationToken.md) |
| POST | `/api/v4/projects/{id}/runners/reset_registration_token` | Reset runner registration token | [View](../operations/postApiV4ProjectsIdRunnersResetRegistrationToken.md) |
| POST | `/api/v4/groups/{id}/runners/reset_registration_token` | Reset runner registration token | [View](../operations/postApiV4GroupsIdRunnersResetRegistrationToken.md) |
