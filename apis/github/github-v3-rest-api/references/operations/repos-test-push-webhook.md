# POST /repos/{owner}/{repo}/hooks/{hook_id}/tests

**Resource:** [repos](../resources/repos.md)
**Test the push repository webhook**
**Operation ID:** `repos/test-push-webhook`

This will trigger the hook with the latest push to the current repository if the hook is subscribed to `push` events. If the hook is not subscribed to `push` events, the server will respond with 204 but no test POST will be generated.

> [!NOTE]
> Previously `/repos/:owner/:repo/hooks/:hook_id/test`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

