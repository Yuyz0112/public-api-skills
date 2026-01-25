# Jobs

Jobs represent processes that handle asynchronous work. A job created when an endpoint requests an action that will be handled asynchronously, such as project or task duplication.

Only the creator of the duplication process can access the duplication status of the new object.

*Note*: With any work that is handled asynchronously (e.g., [project instantation from a template](/reference/instantiateproject), duplicating a [task](/reference/duplicatetask) or [project](/reference/duplicateproject), etc.), the *intermittent states* of newly-created objects may not be consistent. That is, object properties may return different values each time when polled until the job `status` has returned a `succeeded` value.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/jobs/{job_gid}` | Get a job by id | [View](../operations/getJob.md) |
