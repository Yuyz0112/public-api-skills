# ComponentSet

A description of a component set, which is a node containing a set of variants of a component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The key of the component set |
| `name` | string | Yes | Name of the component set |
| `description` | string | Yes | The description of the component set as entered in the editor |
| `documentationLinks` | DocumentationLink[] | No | An array of documentation links attached to this component set |
| `remote` | boolean | No | Whether this component set is a remote component set that doesn't live in this file |

