# Trigger

The `"ON_HOVER"` and `"ON_PRESS"` trigger types revert the navigation when the trigger is finished (the result is temporary). 
`"MOUSE_ENTER"`, `"MOUSE_LEAVE"`, `"MOUSE_UP"` and `"MOUSE_DOWN"` are permanent, one-way navigation.
The `delay` parameter requires the trigger to be held for a certain duration of time before the action occurs.
Both `timeout` and `delay` values are in milliseconds.
The `"ON_MEDIA_HIT"` and `"ON_MEDIA_END"` trigger types can only trigger from a video. 
They fire when a video reaches a certain time or ends. The `timestamp` value is in seconds.

**Type:** oneOf

## Composition

- (inline schema)
- [AfterTimeoutTrigger](AfterTimeoutTrigger.md)
- (inline schema)
- [OnKeyDownTrigger](OnKeyDownTrigger.md)
- [OnMediaHitTrigger](OnMediaHitTrigger.md)
- (inline schema)
