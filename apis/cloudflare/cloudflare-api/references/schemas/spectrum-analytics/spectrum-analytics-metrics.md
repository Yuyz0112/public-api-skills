# spectrum-analytics_metrics

One or more metrics to compute. Options are: 

Metric                    | Name                                | Example                  | Unit
--------------------------|-------------------------------------|--------------------------|--------------------------
count                     | Count of total events               | 1000                     | Count
bytesIngress              | Sum of ingress bytes                | 1000                     | Sum
bytesEgress               | Sum of egress bytes                 | 1000                     | Sum
durationAvg               | Average connection duration         | 1.0                      | Time in milliseconds
durationMedian            | Median connection duration          | 1.0                      | Time in milliseconds
duration90th              | 90th percentile connection duration | 1.0                      | Time in milliseconds
duration99th              | 99th percentile connection duration | 1.0                      | Time in milliseconds.

**Type:** array

Array of object
