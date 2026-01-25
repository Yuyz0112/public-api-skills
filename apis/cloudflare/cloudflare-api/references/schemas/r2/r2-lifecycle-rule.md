# r2_lifecycle-rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abortMultipartUploadsTransition` | object | No | Transition to abort ongoing multipart uploads. |
| `conditions` | object | Yes | Conditions that apply to all transitions of this rule. |
| `deleteObjectsTransition` | object | No | Transition to delete objects. |
| `enabled` | boolean | Yes | Whether or not this rule is in effect. |
| `id` | string | Yes | Unique identifier for this rule. |
| `storageClassTransitions` | any[] | No | Transitions to change the storage class of objects. |

## Nested Fields

### `abortMultipartUploadsTransition`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `condition` | any | No |  |

### `conditions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `prefix` | string | Yes | Transitions will only apply to objects/uploads in the bucket that start with the given prefix, an empty prefix can be provided to scope rule to all objects/uploads. |

### `deleteObjectsTransition`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `condition` | any | No |  |

