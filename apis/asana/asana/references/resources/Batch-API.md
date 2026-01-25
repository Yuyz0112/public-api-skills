# Batch API

There are many cases where you want to accomplish a variety of work in the Asana API but want to minimize the number of HTTP requests you make. For example:

* Modern browsers limit the number of requests that a single web page can
  make at once.
* Mobile apps will use more battery life to keep the cellular radio on
  when making a series of requests.
* There is an overhead cost to developing software that can make multiple
  requests in parallel.
* Some cloud platforms handle parallelism poorly, or disallow it
  entirely.


To make development easier in these use cases, Asana provides a **batch API** that enables developers to perform multiple “actions” by making only a single HTTP request.

#### Making a batch request

To make a batch request, send a `POST` request to `/batch`. Like other `POST` endpoints, the body should contain a `data` envelope. Inside this envelope should be a single `actions` field, containing a list of “action” objects.  Each action represents a standard request to an existing endpoint in the Asana API.

**The maximum number of actions allowed in a single batch request is 10**. Making a batch request with no actions in it will result in a `400 Bad Request`.

When the batch API receives the list of actions to execute, it will dispatch those actions to the already-implemented endpoints specified by the `relative_path` and `method` for each action. This happens in parallel, so all actions in the request will be processed simultaneously. There is no guarantee of the execution order for these actions, nor is there a way to use the output of one action as the input of another action (such as creating a task and then commenting on it).

The response to the batch request will contain (within the `data` envelope) a list of result objects, one for each action. The results are guaranteed to be in the same order as the actions in the request (e.g., the first result in the response corresponds to the first action in the request)

The batch API will always attempt to return a `200 Success` response with individual result objects for each individual action in the request. Only in certain cases (such as missing authorization or malformed JSON in the body) will the entire request fail with another status code. Even if every individual action in the request fails, the batch API will still return a `200 Success` response, and each result object in the response will contain the errors encountered with each action.

#### Rate limiting

The batch API fully respects all of our rate limiting. This means that a batch request counts against *both* the standard rate limiter and the concurrent request limiter as though you had made a separate HTTP request for every individual action. For example, a batch request with five actions counts as five separate requests in the standard rate limiter, and counts as five concurrent requests in the concurrent request limiter. The batch request itself incurs no cost.

If any of the actions in a batch request would exceed any of the enforced limits, the *entire* request will fail with a `429 Too Many Requests` error. This is to prevent the unpredictability of which actions might succeed if not all of them could succeed.

#### Restrictions

Not every endpoint can be accessed through the batch API. Specifically, the following actions cannot be taken and will result in a `400 Bad Request` for that action:

* Uploading attachments
* Creating, getting, or deleting organization exports
* Any SCIM operations
* Nested calls to the batch API

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/batch` | Submit parallel requests | [View](../operations/createBatchRequest.md) |
