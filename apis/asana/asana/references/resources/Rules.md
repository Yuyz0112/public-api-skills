# Rules

[Asana rules](https://help.asana.com/s/article/rules?language=en_US) allow you to automate common patterns
and workflows in Asana. Rules comprise triggers that will automatically perform actions. For example, you
can create a rule to automatically assign a task (action) when a due date is set (trigger).

To support cross-application workflows, the API supports
[incoming web requests](https://developers.asana.com/docs/incoming-web-requests) as a generic trigger to
connect external applications to Asana through rules. This API allows users to set up workflows outside
of Asana that can perform operations on data within Asana.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rule_triggers/{rule_trigger_gid}/run` | Trigger a rule | [View](../operations/triggerRule.md) |
