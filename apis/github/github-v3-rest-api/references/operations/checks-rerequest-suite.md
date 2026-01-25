# POST /repos/{owner}/{repo}/check-suites/{check_suite_id}/rerequest

**Resource:** [checks](../resources/checks.md)
**Rerequest a check suite**
**Operation ID:** `checks/rerequest-suite`

Triggers GitHub to rerequest an existing check suite, without pushing new code to a repository. This endpoint will trigger the [`check_suite` webhook](https://docs.github.com/webhooks/event-payloads/#check_suite) event with the action `rerequested`. When a check suite is `rerequested`, its `status` is reset to `queued` and the `conclusion` is cleared.

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

