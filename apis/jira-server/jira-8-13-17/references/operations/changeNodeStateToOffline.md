# PUT /cluster/node/{nodeId}/offline

**Resource:** [cluster](../resources/cluster.md)
**Operation ID:** `changeNodeStateToOffline`

Change the node's state to offline if the node is reporting as active, but is not alive.
 Don't use this method as an equivalent of running ./stop-jira.sh. This method doesn't shut down
 a node, but only changes its state, so that other nodes don't communicate with it.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

