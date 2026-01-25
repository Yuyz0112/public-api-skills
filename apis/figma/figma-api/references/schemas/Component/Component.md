# Component

A description of a main component. Helps you identify which component instances are attached to.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The key of the component |
| `name` | string | Yes | Name of the component |
| `description` | string | Yes | The description of the component as entered in the editor |
| `componentSetId` | string | No | The ID of the component set if the component belongs to one |
| `documentationLinks` | DocumentationLink[] | Yes | An array of documentation links attached to this component |
| `remote` | boolean | Yes | Whether this component is a remote component that doesn't live in this file |

