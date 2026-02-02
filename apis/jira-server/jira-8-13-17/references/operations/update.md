# PUT /workflowscheme/{id}

**Resource:** [workflowscheme](../resources/workflowscheme.md)
**Operation ID:** `update`

Update the passed workflow scheme.
 <p/>
 The body of the request is a representation of the workflow scheme. Values not passed are assumed to indicate
 no change for that field.
 <p/>
 The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft
 should be created and/or updated when the actual scheme cannot be edited (e.g. when the scheme is being used by
 a project). Values not appearing the body will not be touched.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

