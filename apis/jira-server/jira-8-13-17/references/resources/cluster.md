# cluster

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| DELETE | `/cluster/node/{nodeId}` |  | [View](../operations/deleteNode.md) |
| PUT | `/cluster/node/{nodeId}/offline` |  | [View](../operations/changeNodeStateToOffline.md) |
| GET | `/cluster/nodes` |  | [View](../operations/getAllNodes.md) |
| POST | `/cluster/zdu/approve` |  | [View](../operations/approveUpgrade.md) |
| POST | `/cluster/zdu/cancel` |  | [View](../operations/cancelUpgrade.md) |
| POST | `/cluster/zdu/retryUpgrade` |  | [View](../operations/acknowledgeErrors.md) |
| POST | `/cluster/zdu/start` |  | [View](../operations/setReadyToUpgrade.md) |
| GET | `/cluster/zdu/state` |  | [View](../operations/getState.md) |
