# RelatedIncidentMachineLearningRelationship

The data for a type of relationship where the Incident is related due to our machine learning algorithm.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `grouping_classification` | enum: similar_contents, prior_feedback | No | The classification for why this Related Incident was grouped into this group.
Values can be one of: [similar_contents, prior_feedback], where:
similar_contents - The Related Incident was due to similar contents of the Incidents.
prior_feedback - The Related Incident was determined to be related, based on User feedback or Incident merge/unmerge actions.
 |
| `user_feedback` | object | No | The feedback provided from Users to influence the machine learning algorithm for future Related Incidents. |

## Nested Fields

### `user_feedback`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `positive_feedback_count` | integer | No | The total number of times Users agreed that the Incidents are related. |
| `negative_feedback_count` | integer | No | The total number of times Users disagreed that the Incidents are related. |

