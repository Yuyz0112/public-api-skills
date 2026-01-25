# POST /repos/{owner}/{repo}/check-runs/{check_run_id}/rerequest

**Resource:** [checks](../resources/checks.md)
**Rerequest a check run**
**Operation ID:** `checks/rerequest-run`

Triggers GitHub to rerequest an existing check run, without pushing new code to a repository. This endpoint will trigger the [`check_run` webhook](https://docs.github.com/webhooks/event-payloads/#check_run) event with the action `rerequested`. When a check run is `rerequested`, the `status` of the check suite it belongs to is reset to `queued` and the `conclusion` is cleared. The check run itself is not updated. GitHub apps recieving the [`check_run` webhook](https://docs.github.com/webhooks/event-payloads/#check_run) with the `rerequested` action should then decide if the check run should be reset or updated and call the [update `check_run` endpoint](https://docs.github.com/rest/checks/runs#update-a-check-run) to update the check_run if desired.

For more information about how to re-run GitHub Actions jobs, see "[Re-run a job from a workflow run](https://docs.github.com/rest/actions/workflow-runs#re-run-a-job-from-a-workflow-run)".

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | Forbidden if the check run is not rerequestable or doesn't belong to the authenticated GitHub App |
| 404 | (reference) |
| 422 | Validation error if the check run is not rerequestable |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

