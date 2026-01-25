# GET /event_orchestrations/{id}/unrouted

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Get the Unrouted Orchestration for an Event Orchestration**
**Operation ID:** `getOrchPathUnrouted`

Get a Global Event Orchestration's Rules for Unrouted events.

An Unrouted Orchestration allows you to create a set of Event Rules that will be evaluated against all events that don't match any rules in the Global Orchestration's Router. Events that reach the Unrouted Orchestration will never be routed to a specific Service.

The Unrouted Orchestration evaluates Events sent to it against each of its rules, beginning with the rules in the "start" set. When a matching rule is found, it can modify and enhance the event and can route the event to another set of rules within this Unrouted Orchestration for further processing.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

