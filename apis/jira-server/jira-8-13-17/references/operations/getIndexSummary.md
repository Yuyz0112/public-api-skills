# GET /index/summary

**Resource:** [index](../resources/index.md)
**Operation ID:** `getIndexSummary`

Summarizes index condition of current node.
 <p/>
 Returned data consists of:
 <ul>
 <li><code>nodeId</code> - Node identifier.</li>
 <li><code>reportTime</code> - Time of this report creation.</li>
 <li><code>issueIndex</code> - Summary of issue index status.</li>
 <li><code>replicationQueues</code> - Map of index replication queues, where
 keys represent nodes from which replication operations came from.</li>
 </ul>
 <p/>
 <code>issueIndex</code> can contain:
 <ul>
 <li><code>indexReadable</code> - If <code>false</code> the end point failed to read data from issue index
 (check Jira logs for detailed stack trace), otherwise <code>true</code>.
 When <code>false</code> other fields of <code>issueIndex</code> can be not visible.</li>
 <li><code>countInDatabase</code> - Count of issues found in database.</li>
 <li><code>countInIndex</code> - Count of issues found while querying index.</li>
 <li><code>lastUpdatedInDatabase</code> - Time of last update of issue found in database.</li>
 <li><code>lastUpdatedInIndex</code> - Time of last update of issue found while querying index.</li>
 </ul>
 <p/>
 <code>replicationQueues</code>'s map values can contain:
 <ul>
 <li><code>lastConsumedOperation</code> - Last executed index replication operation by current node from sending node's queue.</li>
 <li><code>lastConsumedOperation.id</code> - Identifier of the operation.</li>
 <li><code>lastConsumedOperation.replicationTime</code> - Time when the operation was sent to other nodes.</li>
 <li><code>lastOperationInQueue</code> - Last index replication operation in sending node's queue.</li>
 <li><code>lastOperationInQueue.id</code> - Identifier of the operation.</li>
 <li><code>lastOperationInQueue.replicationTime</code> - Time when the operation was sent to other nodes.</li>
 <li><code>queueSize</code> - Number of operations in queue from sending node to current node.</li>
 </ul>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

