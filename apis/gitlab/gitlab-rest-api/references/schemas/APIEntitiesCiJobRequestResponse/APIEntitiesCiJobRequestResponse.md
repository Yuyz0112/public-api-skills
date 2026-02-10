# APIEntitiesCiJobRequestResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `token` | string | No |  |
| `allow_git_fetch` | string | No |  |
| `job_info` | [APIEntitiesCiJobRequestJobInfo](APIEntitiesCiJobRequestJobInfo.md) | No |  |
| `git_info` | [APIEntitiesCiJobRequestGitInfo](APIEntitiesCiJobRequestGitInfo.md) | No |  |
| `runner_info` | [APIEntitiesCiJobRequestRunnerInfo](APIEntitiesCiJobRequestRunnerInfo.md) | No |  |
| `inputs` | string | No |  |
| `variables` | string | No |  |
| `steps` | [APIEntitiesCiJobRequestStep](APIEntitiesCiJobRequestStep.md) | No |  |
| `hooks` | [APIEntitiesCiJobRequestHook](APIEntitiesCiJobRequestHook.md) | No |  |
| `image` | [APIEntitiesCiJobRequestImage](APIEntitiesCiJobRequestImage.md) | No |  |
| `services` | [APIEntitiesCiJobRequestService](APIEntitiesCiJobRequestService.md) | No |  |
| `artifacts` | [APIEntitiesCiJobRequestArtifacts](APIEntitiesCiJobRequestArtifacts.md) | No |  |
| `cache` | [APIEntitiesCiJobRequestCache](APIEntitiesCiJobRequestCache.md) | No |  |
| `credentials` | [APIEntitiesCiJobRequestCredentials](APIEntitiesCiJobRequestCredentials.md) | No |  |
| `features` | string | No |  |
| `dependencies` | string | No |  |
| `run` | string | No |  |
| `secrets` | string | No |  |
| `policy_options` | string | No |  |

