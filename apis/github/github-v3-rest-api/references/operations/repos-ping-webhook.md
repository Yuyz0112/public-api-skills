# POST /repos/{owner}/{repo}/hooks/{hook_id}/pings

**Resource:** [repos](../resources/repos.md)
**Ping a repository webhook**
**Operation ID:** `repos/ping-webhook`

This will trigger a [ping event](https://docs.github.com/webhooks/#ping-event) to be sent to the hook.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

